<template>
  <div id="app">
    <Nav />
    <router-view/>
    <BottomBar />
  </div>
</template>

<script>

import Nav from './components/Nav.vue'
import BottomBar from './components/BottomBar.vue'

export default {
  name: 'App',
  components: {
    Nav,
    BottomBar
  }
}
</script>

<style>
#app {
  font-family: "Poppins", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
