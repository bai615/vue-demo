<template>
  <div id="app">
    <img src="./assets/logo.png">
    <router-view/>
    <vuex-test/>
  </div>
</template>

<script>

import VuexTest from './components/VuexTest'

export default {
  name: 'App',
  components: { VuexTest }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
