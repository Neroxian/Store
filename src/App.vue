<template>
  <div id="app">
    <Home/>
    <Acknowledgment/>.
    <Issue/>
  </div>
</template>

<script>
import Acknowledgment from './components/Acknowledgment.vue'
import Home from './components/Home.vue'
import Issue from './components/Issue.vue'

export default {
  name: 'App',
  components: {
    Home,
    Acknowledgment,
    Issue
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Poppins&display=swap');
#app {
  font-family: 'Poppins', sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}
</style>
