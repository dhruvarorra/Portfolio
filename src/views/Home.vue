<template>
  <v-app
    id="home"
    :style="{ background: $vuetify.theme.themes.dark.background }"
  >
    <nav-bar />
    <v-container fluid>
      <v-row>
        <v-col cols="6">
          <v-img src="dhruv.png" contain max-height="500"></v-img>
        </v-col>
        <v-col cols="6">
          <h5 class="red--text text--darken-4 top">Hello I'm Dhruv Arora</h5>
          <h1 class="white--text">Software Developer</h1>
          <p class="grey--text">
            A passionate software developer with a knack for turning innovative ideas into functional applications. With a strong foundation in JavaScript, Vue, React, TypeScript, and Bootstrap.<br>
            I thrive on building efficient and user-friendly software solutions that solve real-world problems.<br />
            
          </p>
    <p class="red--text text--darken-4">At Xlscout</p>

        </v-col>
        <v-col cols="12" class="padd">
          <div class="first" id="project">
            <v-row>
              <v-col cols="12">
                <div class="child bgColor1 higher-card">
                  <v-icon color="#A7121D" x-large class="ml-3">mdi-account-search</v-icon>
                  <h3 class="white--text ml-3 mt-4">JOB Vista</h3>
                  <p class="grey--text ml-3 mt-6">
                    The Job Board Platform <br> enhances job searching <br> and recruitment 
                    by providing <br> personalized recommendations, 
                    <br> application tracking.
                  </p>
                  <v-btn color="#A7121D" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor2 higher-card">
                  <v-icon color="" x-large class="ml-3" dark>mdi-code-tags</v-icon>
                  <h3 class="white--text ml-3 mt-4">Sorting Algorithm <br> Simulator</h3>
                  <p class="grey--text ml-3 mt-6">
                    The Sorting Algorithm <br> Simulator is an interactive <br> tool
                    that visualizes different <br> sorting algorithms in action. 
                  </p>
                  <v-btn color="" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
                <div class="child bgColor1 higher-card">
                  <v-icon color="#A7121D" x-large class="ml-3">mdi-weather-sunny</v-icon>
                  <h3 class="white--text ml-3 mt-4">Weather Forecasting <br> Website</h3>
                  <p class="grey--text ml-3 mt-6">
                    The Weather Forecasting Website<br> is a user-friendly 
                    app built with <br> HTML, CSS, and JavaScript.
                  </p>
                  <v-btn color="#A7121D" dark text>
                    know more
                    <v-icon right>mdi-arrow-right</v-icon>
                  </v-btn>
                </div>
              </v-col>
              <v-col cols="12" class="mt-3">
                <div class="child1">
                  <h1 class="red--text text--darken-4 number">0</h1>
                  <h3 class="white--text">Year Experience</h3>
                </div>
                <div class="child2 mRight">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="red--text text--darken-4">VueJS</h1>
                        <p class="grey--text">Moderate</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="red--text text--darken-4">Javascript</h1>
                        <p class="grey--text">Moderate</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
                <div class="child2">
                  <v-row>
                    <v-col cols="12" class="childcol">
                      <div class="child2 mButton padding bgColor1">
                        <h1 class="red--text text--darken-4">Typescript</h1>
                        <p class="grey--text">Moderate</p>
                      </div>
                    </v-col>
                    <v-col cols="12" class="childcol">
                      <div class="child2 padding bgColor1">
                        <h1 class="red--text text--darken-4">Bootstrap</h1>
                        <p class="grey--text">Moderate</p>
                      </div>
                    </v-col>
                  </v-row>
                </div>
              </v-col>
            </v-row>
          </div>
        </v-col>
        <v-col md="3" offset-md="3" id="about" class="mt-2">
          <h4 class="white--text">FEATURED PROJECTS</h4>
        </v-col>
        <v-col md="3" class="text-end mt-2">
          <v-btn tile color="#A7121D" dark> Glimpse </v-btn>
        </v-col>
        <v-col md="3" offset-md="3" class="mt-negative">
          <v-card class="pa-2 py-12" outlined tile height="250px" color="#1E1E1E">
            <v-img src="1.png" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3" class="mt-negative">
          <v-card class="pa-2 py-12" outlined tile height="250px" color="#1E1E1E">
            <v-img src="3.png" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3" class="mt-0">
          <a href="https://jobvistaaa.netlify.app/" target="_blank" rel="noopener noreferrer">
  <v-btn color="white" dark text class="ml-n4">
    Job Vista
  </v-btn>
</a>

        </v-col>
        <v-col md="3" class="mt-0">
          <a href="https://dhruvkanbanboard.netlify.app/" target="_blank" rel="noopener noreferrer">
  <v-btn color="white" dark text class="ml-n4">
    Kanban Board
  </v-btn>
</a>

        </v-col>
        <v-col md="3" offset-md="3" class="mt-negative">
          <v-card class="pa-2 py-12" outlined tile height="250px" color="#1E1E1E">
            <v-img src="4.png" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3" class="mt-negative">
          <v-card class="pa-2 py-12" outlined tile height="250px" color="#1E1E1E">
            <v-img src="2.png" contain></v-img>
          </v-card>
        </v-col>
        <v-col md="3" offset-md="3" class="mt-0">
         <a href="https://dhruvaroracalculator.netlify.app/" target="_blank" rel="noopener noreferrer">
  <v-btn color="white" dark text class="ml-n4">
    Calculator
  </v-btn>
</a>

        </v-col>
        <v-col md="3" class="mt-0">
         <a href="https://dhruvarorraportfolio.netlify.app/" target="_blank" rel="noopener noreferrer">
  <v-btn color="white" dark text class="ml-n4">
    Portfolio
  </v-btn>
</a>

        </v-col>
        <v-col cols="12" class="padd topInverse">
          <div class="second">
            <div class="secondchild1" id="contact">
              <v-row>
                <v-col cols="7">
                  <h1 class="white--text">Let's work together</h1>
                  <p class="grey--text">
                    dhruvarora8392@gmail.com<br>
                    Software Developer @Xlscout
                  </p>
                </v-col>
                <v-col cols="5">
                  <v-btn tile color="#A7121D" dark class="mt-16">Contact</v-btn>

                  
                </v-col>
              </v-row>
            </div>
          </div>
          <v-toolbar class="topTolbar" color="#111111" dark flat>
            <div style="width: 100%; display: flex; justify-content: center;">
              <v-btn text @click="scroll('home')">Home</v-btn>
              <v-btn text @click="scroll('project')">Skills</v-btn>
              <v-btn text @click="scroll('about')">Project</v-btn>
              <v-btn text @click="scroll('contact')">Contact</v-btn>
            </div>
          </v-toolbar>
        </v-col>
      </v-row>
    </v-container>
    <Footer />
  </v-app>
</template>

<script>
import NavBar from "../components/NavBar.vue";
import Footer from "../components/Footer.vue";

export default {
  name: "Home",
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
  components: {
    NavBar,
    Footer,
  },
  methods: {
    scroll(target) {
      const element = document.getElementById(target);
      if (element) {
        element.scrollIntoView({ behavior: 'smooth', block: 'start' });
      }
    }
  }
};
</script>

<style scoped>
.top {
  margin-top: 180px;
}
.topInverse {
  margin-top: -250px;
}
.topTolbar {
  margin-top: 100px;
}
.first {
  width: 100%;
  height: 610px;
  background: linear-gradient(
    to right,
    #181818,
    #181818 50%,
    #111111 50%,
    #111111 50%
  );
  text-align: center;
  padding: 2rem 2rem;
}
.second {
  width: 100%;
  height: 400px;
  background: #181818;
  text-align: center;
  padding: 2rem 2rem;
}
.secondchild1 {
  display: inline-block;
  background-color: #1e1e1e;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-top: 250px;
}
.child {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  text-align: left;
  margin-right: 8px;
}
.bgColor1 {
  background-color: #1e1e1e;
}
.bgColor2 {
  background-color: #ce1d2a;
}
.child1 {
  display: inline-block;
  padding: 2rem 1rem;
  vertical-align: middle;
  margin-right: 5px;
  width: 240px;
}
.child2 {
  display: inline-block;
  width: 245px;
  vertical-align: middle;
}
.mRight {
  margin-right: 8px;
}
.mButton {
  margin-bottom: 8px;
}
.padding {
  padding: 8px 0;
}
.col-12.padd {
  padding: 12px 0 !important;
}
.col-12.childcol {
  padding: 0 !important;
}
h1.number {
  font-size: 50px;
  font-weight: bold;
}
.higher-card {
  margin-top: -10px;
}
.mt-4 {
  margin-top: 5px; 
}
.mt-2 {
  margin-top: 2px; 
}
.mt-1 {
  margin-top: -2px; 
}
.mt-negative {
  margin-top: -10px; 
}
</style>
