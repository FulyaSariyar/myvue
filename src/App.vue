<template>
  <div id="app">
    <basic-component customText="deneme" />
  </div>
</template>

<script>
import BasicComponent from './components/BasicComponent.vue'
export default {
  components: {
    BasicComponent
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
