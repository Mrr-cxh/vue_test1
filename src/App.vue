<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <Aaa />
    <Bbb />
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import Aaa from "./components/Aaa.vue";
import Bbb from "./components/Bbb.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    Aaa,
    Bbb,
  },
};
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
