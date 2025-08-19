<template>
  <img alt="utm" src="./assets/LOGO.jpeg.jpg">
  <HelloWorld msg="EN PROCESO"/>


  
  <FooterApp />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import FooterApp from './components/FooterApp.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    FooterApp
  }
}
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
