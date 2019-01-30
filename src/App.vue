<template>
  <div id="app">
    <my-title title-name="My journey with Vue"></my-title>
    <img src="./assets/logo.png">
    <router-view/>
  </div>
</template>

<script>
import myTitle from './components/TestComponent'
export default {
  name: 'App',
  components: {myTitle},
  beforeCreate () {
    // before create component
  },
  created () {
    // Render page success
    console.log('component created')
  },
  beforeMount () {
    // before create variable with element
  },
  mounted () {
    // mounth variable of html
  },
  beforeDestroy () {
    // before destory component
  },
  destroyed() {
    // after destory component
  }
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
