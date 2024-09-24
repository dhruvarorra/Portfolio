<template>
  <v-app-bar app color="black" dark flat class="px-8">
    <div class="circular-div">DA</div>
    <v-spacer></v-spacer>
    <v-btn text @click="scroll('home')">Home</v-btn>
    <v-btn text @click="scroll('project')">Skills</v-btn>
    <v-btn text @click="scroll('about')">Project</v-btn>
    <v-btn text @click="scroll('contact')">Contact</v-btn>
  </v-app-bar>
</template>

<script>
export default {
  methods: {
    scroll(refName) {
      const element = document.getElementById(refName);
      element.scrollIntoView({ behavior: "smooth" });
    },
  },
};
</script>

<style>
.circular-div {
  width: 40px;  
  height: 40px; 
  background-color: #A7121D; 
  border-radius: 50%;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
  font-size: 20px; 
  font-weight: bold; 
  margin-left: 16px; 
}
</style>
