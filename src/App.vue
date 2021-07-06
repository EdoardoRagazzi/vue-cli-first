<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <Title msg="La mia prima App con vue Cli 🌍" /> -->
    <Jumbotroon />
  </div>
</template>

<script>
import Title from "./components/Title.vue";
import Jumbotroon from "./components/Jumbotroon.vue";

export default {
  name: "App",
  components: {
    Title,
    Jumbotroon,
  },
};
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
