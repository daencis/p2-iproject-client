<template>
  <div id="app">
    <navbar></navbar>
    <router-view/>
  </div>
</template>
<script>
import Navbar from './components/Navbar.vue'
export default {
  components: { Navbar },
  name: "App",
  
}
</script>
<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
