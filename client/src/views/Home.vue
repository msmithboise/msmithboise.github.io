<template>
  <v-app>
    <v-content>
      <section>
        <v-parallax grid-list-md text-xs-center>

          <v-toolbar>
            <v-toolbar-side-icon></v-toolbar-side-icon>
            <v-toolbar-title>Title</v-toolbar-title>
            <v-spacer></v-spacer>
            <v-toolbar-items class="hidden-sm-and-down">
              <v-btn flat>Link One</v-btn>
              <v-btn flat>Link Two</v-btn>
              <v-btn flat>Link Three</v-btn>
            </v-toolbar-items>
          </v-toolbar>

          <v-layout row wrap>

            <img src="@/assets/modern.jpeg" height="700" width="1800" alt="modern">
            <h1 class="hero-heading">Michael Smith</h1>
            <p class="hero-paragraph">Developer | Designer</p>
          </v-layout>
        </v-parallax>
      </section>

      <section>
        <v-container fluid grid-list-sm text-xs-center class="profs-one">
         
          <h1 style="margin-bottom: 5%">Proficiencies</h1>
        
          <v-layout row wrap>
            <v-flex sm12>
             <v-card hover>

              <i class="fab fa-html5"></i>
              <i class="fab fa-css3"></i>
              <i class="devicon-bootstrap-plain colored icons"></i>
            </v-card>
              <i class="devicon-csharp-plain colored"></i>
              <i class="devicon-express-original-wordmark colored"></i>
              <i class="devicon-git-plain colored"></i>
            </v-flex>
          </v-layout>
        </v-container>
        <v-container fluid grid-list-sm text-xs-center class="profs-two">
          <v-layout row wrap>
            <v-flex>
              <i class="devicon-javascript-plain colored"></i>
              <i class="devicon-mongodb-plain-wordmark colored"></i>
              <i class="devicon-mysql-plain-wordmark colored"></i>
              <i class="devicon-nodejs-plain-wordmark colored"></i>
              <i class="devicon-vuejs-plain-wordmark colored"></i>
              <i class="devicon-wordpress-plain colored"></i>
            </v-flex>
          </v-layout>
        </v-container>
      </section>












    </v-content>
  </v-app>
</template>





<script>





</script>


<style>
  /* v-card{
    background-color: blueviolet;
  } */

  .profs-one{
    background-color: #f9f9f9;
  }

  .profs-two{
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