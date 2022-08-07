<template>
<div class="wrapper">
    <div class="main-container">
    <div class="container-one">
      <div class="profile">
        <img src="../assets/habib.png" alt="">
        <h3>Md Habibur Rahman</h3>
        <p>Software Developer</p>
      </div>
      <div class="social-links">
        
          <div class="link">
            <div class="link">
            <img src="../assets/email.png" alt="">
            <a href="mrahman162123@bscse.uiu.ac.bd"><h5>Gmail</h5></a>
          </div>
            <img src="../assets/github.png" alt="">
            <a href="https://github.com/habib162"><h5>Github</h5></a>
          </div>
          <div class="link">
            <img src="../assets/linkedin.png" alt="">
            <a href="https://www.linkedin.com/in/m
              d-habibur-rahman-68a43b207/
              "><h5>Linkedin</h5></a>
          </div>
          
      </div>
    </div>
    <div class="container-two">
      <div class="about-me">
        <h1>About me</h1>
        <p>Hello there, I just completed my
          graduation from a reputable
          university looking to advance
          my career by joining a company
          to assist them, build amazing
          relationships and achieve
          success.
        </p>
        <h1>Objective</h1>
        <p>Looking for a position with an
            organization that will allow me to
            put my technical abilities to good
            use and expand my knowledge to
            aid in the process of organizational
            and personal growth.
        </p>
      </div>
      <div class="technology-section">
        <h1>Technologies Studied</h1>
        <div class="logos">
          <img src="../assets/php.png" alt="">
          <img src="../assets/laravel.png" alt="">
          <img src="../assets/js.png" alt="">
          <img src="../assets/html.png" alt="">
          <img src="../assets/css.png" alt="">
          <img src="../assets/sql.png" alt="">
          <img src="../assets/logo.png" alt="">
        </div>
      </div>
      <div class="button-container">
        <div class="project-button">
          <a href="https://github.com/habib162?tab=repositories">My project</a>
        </div>
        <div class="project-button">
          <a href="https://drive.google.com/file/d/1wMDeMcaKuOnhQctweVYnA_9Cnq9NG6cB/view?usp=sharing" download target="_blank">My Resume</a>
        </div>
      </div>
    </div>
  </div>
</div>
</template>

<script>
    
export default {
    name:'HoMe'

}
</script>

<style scoped>
.wrapper{
  display: flex;
  justify-content: center;
  padding-top:20px ;
}
  img{
    height: 20px;
  }
  .main-container{
    display: flex;
    flex-direction: row;
    background-color: #cecece;
    border-radius: 25px;
    width: 70%;
    background-color: #b2c4d6;
    box-shadow: rgb(0,0,0,0.24) 0px 3px 8px;
  }
  .container-one{
    background-color: #2a2626;
    color: #fff;
    padding: 2.5%;
    width: 30%;
    border-radius: 25px;
    box-shadow: rgb(0,0,0,0.24) 0px 3px 8px;
  }
  .profile img{
    height: 5rem;
    border-radius: 50%;
    width: 5rem;

  }
  .link a{
    text-decoration: none;
    color: #fff;
    font-size: 10px;
  }
  .link img{
    height: 2rem;
    border-radius: 25px;

  }
  .about-me{
    text-align: left;
  }
  .container-two{
    width: 70%;
    margin: 2.5%;
  }
  .logos img{
    height: 2.5rem;
    border-radius: 25px;
    padding: 5px;
  }
  .button-container{
    margin-top: 5%;
    display:flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;


  }
  .project-button{
    background-color: #370fc6;
    margin:5px;
    padding: 5px;
    border-radius: 15px;
  }
  .project-button:hover{
    background-color: #563cb4;
    margin:5px;
    padding: 5px;
    border-radius: 15px;
  }
  .project-button a{
    text-decoration: none;
    color: #fff;

  }

  @media screen and(max-widh:950px) {
    .main-container{
      width: 95%;
    }
  }
</style>