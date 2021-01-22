<template>
  <div id="app">
    <Mark/>
  </div>
</template>

<script>
import Mark from './components/Mark.vue'

export default {
  name: 'App',
  components: {
    Mark
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
