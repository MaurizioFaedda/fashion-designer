<template>
  <div id="app">
    <NavBar />
    <Jumbotron />
    <Section />
    <contacts />
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import Jumbotron from "./components/Jumbotron.vue";
import Section from "./components/Section.vue";
import Contacts from "./components/Contacts.vue";

export default {
  name: "App",
  components: {
    NavBar,
    Jumbotron,
    Section,
    Contacts,
  },
};
</script>

<style lang="scss">
@import "./assets/scss/app.scss";
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
