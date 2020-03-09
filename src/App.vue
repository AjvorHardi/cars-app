<template>
  <div id="app">
    <AppCars/>
    <router-link to="/cars">
      Cars
    </router-link>
  </div>
</template>

<script>
import AppCars from './components/AppCars.vue'

export default {
  name: 'App',
  components: {
    AppCars
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
