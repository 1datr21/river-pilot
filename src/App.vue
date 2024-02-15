<template>
  <img alt="Vue logo" src="./assets/logo.jpg" width="200">
  <HelloWorld msg="ЛОЦМАН"/>
  <RPField />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import RPField from './components/RPField.vue'

export default {
  name: 'App',
  components: {
    HelloWorld, RPField
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
