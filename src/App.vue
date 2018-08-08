<template>
  <div id="app">
    <header-bar></header-bar>
    <div id="nav">
    </div>
    <router-view/>
  </div>
</template>

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

<script>
  import HeaderBar from './components/header-bar/HeaderBar.vue';

  export default {
      components: {
          HeaderBar
      }
  }
</script>
