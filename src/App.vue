<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Wasssuuup msg="Welcome to Bilals vue app"/>
  </div>
</template>

<script>
import Wasssuuup from './components/Wasssuuup.vue'

export default {
  name: 'App',
  components: {
    Wasssuuup
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
