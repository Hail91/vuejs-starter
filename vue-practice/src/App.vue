// Application UI here inside template.
<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <test-component message="Hi Vue! :)" count="0" />
  </div>
</template>

<script>
// Imports need to be inside of script tag.
import HelloWorld from "./components/HelloWorld.vue";
import testComponent from "./components/testComponent.vue";

export default {
  name: "App",
  components: {
    HelloWorld,
    testComponent
  }
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
