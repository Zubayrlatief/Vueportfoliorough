<template>
    <div class="main-container">
      <div class="container-one">
      <div class="profile">
        <img src="https://i.postimg.cc/ctRFcy3N/IMG-20240103-WA0084.jpg" alt="">
        <h3>Zubayr Abdullatief</h3>
        <p>Software Dev</p>   
    </div>
    <div class="social-links">
        <div class="link">
            <img src="https://zubayrlatief.github.io/hermessfitness.hostedimages/images.png" alt="">
            <a href=""><h4>Instagram</h4></a>
        </div>
        <div class="link">
            <img src="https://zubayrlatief.github.io/portfolio_hostedImages/images.png" alt="">
            <a href=""><h4>LinkedIn</h4></a>
        </div>
        <div class="link">
            <img src="https://zubayrlatief.github.io/portfolio_hostedImages/github.jpg" alt="">
           <a href=""><h4>Git Hub</h4></a>
        </div>
     </div>
   </div>
 <div class="container-two">
    <div class="about-me">
        <h1>
            Zubayr Abdullatief</h1>
        <p>I am a effecient software developer that aspires<br>
           to hone in his skills.<br>
           I am passionate about learning and gaining more skills.<br>
        
           i studied at Life Choices coding academy becoming proficient in Javascript, Html and CSS.<br>
           Frameworks such as Vue.js, Node js, and Sql.<br>
           CSS procientcy aquired us to do Bootstarp however having a passion for CSS Tailwind was a must for me to self-learn.
        </p>
    </div>
    <div class="framework-section">
        <h1>Proficient Frameworks</h1>
        <div class="framework">
            <img src="https://zubayrlatief.github.io/portfolio_hostedImages/html3d.png" alt="">
            <img src="https://zubayrlatief.github.io/portfolio_hostedImages/javascript3d.png" alt="">
            <img src="https://zubayrlatief.github.io/portfolio_hostedImages/CSS.png" alt="">
            <img src="https://zubayrlatief.github.io/portfolio_hostedImages/html.jpg" alt="">
            <img src="https://zubayrlatief.github.io/portfolio_hostedImages/bootstrap3d.png" alt="">
            <img src="https://zubayrlatief.github.io/portfolio_hostedImages/tailwind2d.png" alt="">
        </div>
    </div>
    <div class="button-container">
        <div class="projects-button">
            <a href="">My Projects</a>
        </div>
        <div class="projects">
            <a href="https://javascript-eomp-2.vercel.app/">Ecomerce responsive site</a>
            <a href="http://"></a>
        </div>
        <div class="projects-button">
            <a href="">My resume</a>
        
      </div>
    </div>
 </div>
 </div>
</template>

<script>
export default{

}
</script>

<style scoped>
   img {
    height: 20px;
   }
   .main-container{
    display: flex;
    flex-direction: row;
    background-color: rgb(81, 151, 169);
    border-radius: 25px;
   }
   .container-one{
     background-color: rgb(35, 113, 135);
     padding: 2.5%;
     width: 30%;
     border-radius: 25px;
   }
   .container-two{
    background-color: (8, 151, 169);
    margin: 2.5%;
    width: 70%;
   }
   .profile img{
    height: 10rem;
   }
   .link a{
    text-decoration: none;
    color: rgb(7, 1, 1);
    font-size: 16px;
   }
   .framework{
    height: 2.5rem;
   }
   .button-container{
    margin-top: 5px;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;

   }
   .projects-button{
    display: grid;
    background-color: rgb(19, 155, 155);
    border-radius: 15px;
    padding: 5px;
    margin: 5px;
    }
    .projects{
        text-decoration: none;
        color: white;
    }

</style>