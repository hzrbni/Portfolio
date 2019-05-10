<template>
  <div id="app">
    <NavBar/>
    <Welcome/>
    <About/>
    <Skills/>
    <Projects/>
    <HireMe/>
  </div>
</template>

<script>
import "materialize-css/dist/css/materialize.css";
import NavBar from "./components/NavBar.vue";
import Welcome from "./components/Welcome.vue";
import About from "./components/About.vue";
import Skills from "./components/Skills.vue";
import Projects from "./components/Projects.vue";
import HireMe from "./components/HireMe.vue";

export default {
  name: "app",
  components: {
    NavBar,
    Welcome,
    About,
    Skills,
    Projects,
    HireMe
  },
  data() {
    return { title: "Hazar Albunni" };
  }
};
</script>

<style lang="scss">
@import "./assets/sass/style.scss";
</style>
