<template>
  <Excel_View/>
</template>

<script>
import Excel_View from './components/Excel_View.vue'

export default {
  name: 'App',
  components: {
    Excel_View
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
