<template>
 <div id="app">

  <Home/>
  <ProjectCard/>
 </div>

</template>

<script>

// import Navbar from './components/Navbar.vue'
import Home from './components/Home.vue'
import ProjectCard from './components/ProjectCard.vue'

export default {
  name: 'App',
  data(){
    return {
      title: 'Portfolio'
    }
  },
  components:{
    Home,
    ProjectCard
}
}
</script>

<style>
body{
  margin: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif; 
   -webkit-font-smoothing: antialiased; 
   -moz-osx-font-smoothing: grayscale;
   text-align: center;
   color: #2c3e50;
  background-color: #d6edff;
}
</style>
