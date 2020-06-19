<template>
  <div id="app">
    <Website />
  </div>
</template>

<script>
import Website from './components/Website.vue'

export default {
  name: 'App',
  components: {
    Website
  }
}
</script>

<style>
@import url('https://fonts.googleapis.com/css2?family=Source+Code+Pro:wght@600&display=swap');

#app {
  font-family: 'Souce Code Pro', monospace;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #fffafa;
  padding-top: 10%;
  padding-left: 25%;
  padding-right: 25%;
  padding-bottom: 20%;
  background: #1D1D1D;
}
</style>
