<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png" />
    <HelloWorld msg="Welcome to Your Vue.js App" />
    <FirstComponent :msg="test"></FirstComponent>
  </div>
</template>

<script>
import HelloWorld from "./components/HelloWorld.vue";
import FirstComponent from "./components/FistSingleComponent";

export default {
  name: "app",
  data: function() {
    return {
      test: "我是test"
    };
  },
  components: {
    HelloWorld,
    FirstComponent
  }
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
