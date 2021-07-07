<template>
<video autoplay muted loop id="myVideo">
  <source src="./assets/ru_flag.mp4" type="video/mp4">
</video>
<div id="content">
  <img alt="Vue logo" src="./assets/gone-phisin-brutalwisconsin.png">
  <HelloWorld msg="Welcome to Your New Hell.js"/>
</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'App',
  components: {
    HelloWorld
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
#myVideo {
  position: fixed;
  right: 0;
  bottom: 0;
  min-width: 100%;
  min-height: 100%;
}
#content {
  position: fixed;
  bottom: 0;
  color: #f1f1f1;
  width: 100%;
  padding: 20px;
}
</style>
