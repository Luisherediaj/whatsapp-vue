<template>
  <div id="app">
    <!-- <HelloWorld msg="Welcome to Your Vue.js App"/> -->
    <Home></Home>
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue';
import Home from './components/Home.vue';

export default {
  name: 'App',
  components: {
    Home
  },
}
</script>

<style>
/* #app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
} */

body {
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100%;
    height: 100vh;
    background: linear-gradient(180deg, #019789 0%,#019789 15%, #d9dbd5 15%, #d9dbd5 100%);
    background-repeat: no-repeat;
}
</style>
