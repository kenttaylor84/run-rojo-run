<template>
<video autoplay muted loop id="myVideo">
  <source src="./assets/ru_flag.mp4" type="video/mp4">
</video>
<div id="content">
  <!-- TODO?: nav -->
  
  <HelloWorld msg="в настоящее время ведется строительство"/>
  <!-- TODO: running timer -->

  <!-- TODO: more content -->
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
body {
  margin: 0px;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  /* text-align: center; */
  color: #2c3e50;
  /* margin-top: 20px; */
  margin: 0px;
}
#myVideo {
  position: fixed;
  right: 0;
  bottom: 0;
  min-width: 100%;
  min-height: 100%;
}
#content {
  position: absolute;
  color: black;
  width: 100%;
  margin: 0px;
  /* text-align: center; */
}
</style>
