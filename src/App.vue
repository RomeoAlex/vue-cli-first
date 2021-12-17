<template>
  <div id="app">
    <!-- riutilizzo l'immagine -->
    <img alt="Vue logo" src="./assets/logo.png" />
    <Title msg="La mia prima app con Vue CLI" />
    <Hero/>
  </div>
</template>

<script>
import Title from "./components/Title.vue";
import Hero from "./components/Hero.vue";

export default {
  name: "App",
  components: {
    Title,
    Hero,
  },
};
</script>

<style>
*{
    margin: 0;
    padding:0;
    box-sizing: border-box;
}
#app {
  
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
