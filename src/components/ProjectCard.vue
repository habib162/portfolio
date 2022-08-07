<template>
<div class="main-container">
    <div class="project-card" v-for="(items,index) in projectData.ProjectsArray" v-bind:key="items">
        <h2>{{projectData.ProjectsArray[index].Title}}</h2>
        <p>{{projectData.ProjectsArray[index].Details}}</p>
        <p>{{projectData.ProjectsArray[index].Technology}}</p>
        <div class="links">
            <a :href="projectData.ProjectsArray[index].Link1" target="_blank"><img src="../assets/github.png" alt=""></a>
        </div>
    </div>
   
</div>
</template>

<script>
import jsonData from "/projects.json"

export default {  
    data(){
        return {
             projectData: jsonData
        }
    }
}
</script>

<style scoped>
   
    .main-container{
        margin-top: 5%;
        display:flex;
        flex-wrap: wrap;
        justify-content: center;
        align-items: center;
        
    }
     .project-card{
        margin: 10px;
        flex-wrap: 0 0 40%;
        padding: 10px;
        width: 60%;
        background-color: #fff;
        border-radius: 25px;
        box-shadow: rgb(0,0,0,0.24) 0px 3px 8px;

    }
.links{
    display: flex;
    flex-direction: row;
    align-items: center;
    justify-content: flex-end;
}
.links img{
    height: 1.5rem;
    margin: 5px;
}
</style>