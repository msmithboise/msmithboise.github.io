<template>

  <v-app dark>
    <v-content>

          <v-toolbar class="navbar">
            <v-toolbar-side-icon></v-toolbar-side-icon>
            <v-toolbar-title>Title</v-toolbar-title>
            <v-spacer></v-spacer>
            <v-toolbar-items class="hidden-sm-and-down">
              <v-btn flat>Link One</v-btn>
              <v-btn flat>Link Two</v-btn>
              <v-btn flat>Link Three</v-btn>
            </v-toolbar-items>
          </v-toolbar>

<v-parallax
      dark
      height="700"
      src="https://images.unsplash.com/photo-1521067842-8d1618327b7f?ixlib=rb-0.3.5&s=2de7e01ca75a5a455d832a29d379583f&auto=format&fit=crop&w=1489&q=80.jpg"
    >
      <v-layout
        align-center
        column
        justify-center
      >
        <h1 class="display-2 font-weight-thin mb-3 heading">Michael Smith</h1>
        <h4 class="heading">Developer | Designer</h4>
      </v-layout>
    </v-parallax>

 <v-container  fluid grid-list-sm text-xs-center class="profs-one">
         
          <h1 style="margin-bottom: 5%">Proficiencies</h1>
        
         <v-layout >
            <v-flex >
             
             
              <i class="devicon-bootstrap-plain colored icons px-3"></i>
              
             <i class="fab fa-html5 pa-4"></i>
              <i class="fab fa-css3 pa-4"></i>
              <i class="devicon-csharp-plain colored pa-4"></i>
              <i class="devicon-javascript-plain colored pa-4"></i>
              <i class="devicon-mongodb-plain-wordmark colored pa-4"></i>
              <v-spacer></v-spacer>
              <i class="devicon-mysql-plain-wordmark colored pa-4"></i>
              <i class="devicon-express-original-wordmark colored pa-4"></i>
              <i class="devicon-git-plain colored pa-4"></i>
              <i class="devicon-nodejs-plain-wordmark colored px-4"></i>
              <i class="devicon-vuejs-plain-wordmark colored pa-4"></i>
              <i class="devicon-wordpress-plain colored pa-4"></i>

             
            
            
            </v-flex>
          </v-layout>

           <v-layout row wrap>
            <v-flex sm12>
             <v-card>
            </v-card>
            </v-flex>
          </v-layout>
        </v-container>




        
        <v-parallax 
        
        src="https://images.unsplash.com/photo-1515462277126-2dd0c162007a?ixlib=rb-0.3.5&s=307ff4c303f8e971b819931a3cc60796&auto=format&fit=crop&w=1535&q=80.jpg" height="700" width="1800" alt="design">
       
          <v-layout column align-center justify-center>
            <div class="headline white--text mb-3 text-xs-center">Who I am:</div>

            <em>Design has always fascinated me.</em>
            <em>How something breathtaking starts as a mere thought..</em>
            <em>How a simple idea brought to life can impact someone elses.</em>
            <em>My name is Michael Smith</em>
            <em>I am a developer</em>
            <em>And I wouldn't have it any other way...</em>



            



            <v-btn
              class="blue lighten-2 mt-5"
              dark
              large
              href="/pre-made-themes"
            >
              Contact Me
            </v-btn>
          </v-layout>
        </v-parallax>
      

        <v-container fluid grid-list-sm text-xs-center class="portfolio">
          <h1 class="portfolio-title" style="color:#212121;">Portfolio</h1>
        <v-layout row wrap>
          <v-flex pa-5>
           <div>
            <img src="@/assets/pokemonslap.png" class="elevation-24" height="250" width="400" alt="slap">
           </div>

             <img src="@/assets/inspire.png" class="elevation-24" height="250" width="400" alt="inspire">
            
            <img src="@/assets/trillo.png" class="elevation-24" height="250" width="400" alt="trillo">

             

 
           <img src="@/assets/vuemusic.png" class="elevation-24"  height="250" width="400" alt="vuemusic">
         


           <img src="@/assets/battlecatz.png" class="elevation-24"  height="250" width="400" alt="battlecatz">
            
            
            </v-flex>
          </v-layout>
        </v-container>
    











    </v-content>
  </v-app>
</template>





<script>
</script>


<style>
/* v-card{
    background-color: blueviolet;
  } */
.heading {
  color: #212121;
}
.profs-one {
  background-color: #212121;
}

.navbar {
  background-color: #212121;
}

.profs-two {
  background-color: #f9f9f9;
}

.portfolio-title {
  color: #f9f9f9;
}

.portfolio {
  background-color: #f9f9f9;
}
.hero {
  background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5));

  height: 100%;

  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  position: relative;
}

.hero-heading {
  text-align: center;
  position: absolute;
  top: 30%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
}

.hero-paragraph {
  text-align: center;
  position: absolute;
  top: 35%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
}

.heading-one {
  text-align: center;

  top: 45%;
  left: 50%;
  transform: translate(-50%, -50%);
  color: white;
}

i {
  font-size: 8em;
}
</style>