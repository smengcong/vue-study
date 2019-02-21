<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png"> -->
    <!-- <HelloWorld msg="Welcome to Your Vue.js App1" test="smc11"/> -->
    <smc />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
import smc from './components/smc1.vue'

export default {
  name: 'app',
  components: {
    // HelloWorld,
    smc
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #56a5f3;
  /* margin-top: 60px; */
}
</style>
