<template>

  <v-app dark>
    <v-content>

      <!-- <v-toolbar class="navbar">
            <v-toolbar-side-icon></v-toolbar-side-icon>
            <!<v-toolbar-title>Title</v-toolbar-title> -->
      <v-spacer></v-spacer>
      <!-- <v-toolbar-items class="hidden-sm-and-down">

      </v-toolbar-items> -->
      <!-- </v-toolbar> -->

      <v-parallax dark height="900" src="https://images.unsplash.com/photo-1521067842-8d1618327b7f?ixlib=rb-0.3.5&s=2de7e01ca75a5a455d832a29d379583f&auto=format&fit=crop&w=1489&q=80.jpg">
        <v-layout align-center column justify-center>
          <h1 class="display-2 font-weight-thin mb-3 heading">Michael Smith</h1>
          <h4 class="heading">Developer | Designer</h4>
        </v-layout>
      </v-parallax>


      <!-- proficiencies -->

      <v-container fluid grid-list-sm text-xs-center class="profs-one">



         <h1 class="heading display-1 font-weight-thin mb-3 mt-3" style="color:#f9f9f9;">Proficiencies</h1>


<div class="prof-wrap">
      
       

            <i class="devicon-bootstrap-plain colored icons px-3"></i>

            <i class="fab fa-html5 pa-4"></i>
            <i class="fab fa-css3 pa-4"></i>
            <i class="devicon-csharp-plain colored pa-4"></i>
            <i class="devicon-javascript-plain colored pa-4"></i>
            <i class="devicon-mongodb-plain-wordmark colored pa-4"></i>
          
            <i class="devicon-mysql-plain-wordmark colored pa-4"></i>
            <i class="devicon-express-original-wordmark colored pa-4"></i>
            <i class="devicon-git-plain colored pa-4"></i>
            <i class="devicon-nodejs-plain-wordmark colored px-4"></i>
            <i class="devicon-vuejs-plain-wordmark colored pa-4"></i>
            <i class="devicon-wordpress-plain colored pa-4"></i>
  </div>

      </v-container>





      <v-parallax src="https://images.unsplash.com/photo-1468325089340-2ec20e175048?ixlib=rb-0.3.5&ixid=eyJhcHBfaWQiOjEyMDd9&s=043463682fd9679a9588c876fd72ab34&auto=format&fit=crop&w=1652&q=80.jpg"
        height="700" width="1800" alt="design">

        <v-layout column align-center mt-5>
          <div class="heading display-1 font-weight-thin mb-3 ">Designs</div>
<!-- designs -->

<div class="seperate mt-5 designs-wrap">
             <a href="https://experiencecfc.com/">
                <img src="@/assets/cfc.png" class="elevation-24" height="250" width="400" alt="inspire">
              </a>
            
              <a href="http://sweethopeinc.com/">
            <img src="@/assets/sweethope.png" class="elevation-24" height="250" width="400" alt="trillo">
            </a>

          </div>

        </v-layout>
      </v-parallax>


      <v-container  text-xs-center class="portfolio">
        <h1 class="  display-1 font-weight-thin mb-3" style="color:#f9f9f9;">Applications</h1>
      

          <v-flex>



<!-- Portfolio -->
<div class="portfolio-wrap">
<v-hover>
    <v-card
      slot-scope="{ hover }"
      class="mx-auto"
      color="grey lighten-4"
     max-width="400"
    >
<a href="https://msmithboise.github.io/Slap-emon/">
      <v-img
        :aspect-ratio="16/9"
       :src="require('@/assets/pokemonslap.png')"
       class="elevation-24" height="250" width="400" alt="slap"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out black darken-2 v-card--reveal display-1 white--text"
            style="height: 100%;"
          >
           <h1>Pokemon Slap</h1>  | 
           
          <h3>Made with Javscript</h3> 
          </div>
        </v-expand-transition>
      </v-img>
        </a>
      
    </v-card>
  </v-hover>



  <!-- inspire-->

<v-hover>
    <v-card
      slot-scope="{ hover }"
      class="mx-auto"
      color="grey lighten-4"
      max-width="400"
    >
<a href="https://msmithboise.github.io/inspire/">
      <v-img
        :aspect-ratio="16/9"
       :src="require('@/assets/inspire.png')"
       class="elevation-24" height="250" width="400" alt="slap"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out black darken-2 v-card--reveal display-1 white--text"
            style="height: 100%;"
          >
           <h1>Inspire</h1>  | 
           
          <h3>Made with Javscript</h3> 
          </div>
        </v-expand-transition>
      </v-img>
        </a>
      
    </v-card>
  </v-hover>






  <!-- party ox-->

<v-hover>
    <v-card
      slot-scope="{ hover }"
      class="mx-auto"
      color="grey lighten-4"
      max-width="400"
    >
<a href="https://partyox.herokuapp.com/#/">
      <v-img
        :aspect-ratio="16/9"
       :src="require('@/assets/partyox.png')"
       class="elevation-24" height="250" width="400" alt="slap"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out black darken-2 v-card--reveal display-1 white--text"
            style="height: 100%;"
          >
           <h1>Party Ox</h1>  | 
           
          <h3>Made with Vue.Js | Node.Js | Express</h3> 
          </div>
        </v-expand-transition>
      </v-img>
        </a>
     
    </v-card>
  </v-hover>








  <!-- Trillo-->

<v-hover>
    <v-card
      slot-scope="{ hover }"
      class="mx-auto"
      color="grey lighten-4"
      max-width="400"
    >
<a href="https://trillo-kanban.herokuapp.com/">
      <v-img
        :aspect-ratio="16/9"
       :src="require('@/assets/trillo.png')"
       class="elevation-24" height="250" width="400" alt="slap"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out black darken-2 v-card--reveal display-1 white--text"
            style="height: 100%;"
          >
           <h1>Trillo</h1>  | 
           
          <h3>Made with Vue.Js | Vuetify | Node.Js</h3> 
          </div>
        </v-expand-transition>
      </v-img>
        </a>
      
    </v-card>
  </v-hover>

  <!-- Music Is Fun-->

<v-hover>
    <v-card
      slot-scope="{ hover }"
      class="mx-auto"
      color="grey lighten-4"
      max-width="400"
    >
<a href="https://msmithboise.github.io/Musicisfun/">
      <v-img
        :aspect-ratio="16/9"
       :src="require('@/assets/vuemusic.png')"
       class="elevation-24" height="250" width="400" alt="slap"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out black darken-2 v-card--reveal display-1 white--text"
            style="height: 100%;"
          >
           <h1>Music is fun</h1>  | 
           
          <h3>Made with Javascript | Axios</h3> 
          </div>
        </v-expand-transition>
      </v-img>
        </a>
    
    </v-card>
  </v-hover>


  <!-- Battle Catz-->

<v-hover>
    <v-card
      slot-scope="{ hover }"
      class="mx-auto"
      color="grey lighten-4"
      max-width="400"
    >
<a href="https://msmithboise.github.io/battle-cards/#/">
      <v-img
        :aspect-ratio="16/9"
       :src="require('@/assets/battlecatz.png')"
       class="elevation-24" height="250" width="400" alt="slap"
      >
        <v-expand-transition>
          <div
            v-if="hover"
            class="d-flex transition-fast-in-fast-out black darken-2 v-card--reveal display-1 white--text"
            style="height: 100%;"
          >
           <h1>Battle Catz</h1>  | 
           
          <h3>Made with Vue.Js | Axios</h3> 
          </div>
        </v-expand-transition>
      </v-img>
        </a>
    
    </v-card>
  </v-hover>

  </div>
   
          </v-flex>
      
      </v-container>

      <v-footer light height="auto">
        <v-card class="flex" flat tile>
          <v-card-title class="grey darken-4">
            <strong class="subheading"></strong>

            <v-spacer></v-spacer>

            <v-btn v-for="icon in icons" :key="icon" class="mx-3" dark icon>
              <v-icon size="24px">{{ icon }}</v-icon>
            </v-btn>
          </v-card-title>

          <v-card-actions class="grey darken-3 justify-center">
            <strong></strong>
          </v-card-actions>
        </v-card>
      </v-footer>











    </v-content>
  </v-app>
</template>




<script>
export default {
  data: () => ({
    icons: [
      "fab fa-facebook",
      "fab fa-twitter",
      "fab fa-google-plus",
      "fab fa-linkedin",
      "fab fa-instagram"
    ]
  })
};
</script>


<style>
.prof-wrap {
  display: flex;
  flex-flow: row wrap;
}

.portfolio-wrap {
  display: flex;
  flex-flow: row wrap;
  align-content: center;
}

.designs-wrap {
  display: flex;
  flex-flow: row wrap;
}

.v-card--reveal {
  display: flex;
  justify-content: center;
  align-items: center;
  bottom: 0;
  opacity: 0.8;
  position: absolute;
  width: 100%;
}

h1 {
  font-size: 3vh;
}

.seperate {
  display: flex;
  align-items: center;
}

.overlay {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  height: 100%;
  width: 100%;
  opacity: 0;
  transition: 0.5s ease;
  background-color: #008cba;
}

.container:hover .overlay {
  opacity: 1;
}

.text {
  color: #050505;
  font-size: 6vh;
  position: absolute;
  top: 50%;
  left: 50%;
  -webkit-transform: translate(-50%, -50%);
  -ms-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  text-align: center;
}

em {
  color: #050505;
}

.heading {
  color: #212121;
}

.profs-one {
  background-color: #050505;
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
  background-color: #050505;
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