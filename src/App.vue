<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <br>
  <img style="height: 180px; width: 180px;" alt="foto" src="./assets/Te_Quiero.jpeg">
  <HelloWorld msg="Welcome to Your Vue.js App"/>
  <HefziBa></HefziBa>
  <PasaTiempos></PasaTiempos>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import HefziBa from './components/HefziBa.vue';
import PasaTiempos from './components/PasaTiempos.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    HefziBa,
    PasaTiempos
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
