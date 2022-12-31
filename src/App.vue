<template>
  <GuitarData msg="Oh, hi."/>
</template>

<script>
import GuitarData from './components/GuitarData.vue'

export default {
  name: 'App',
  components: {
    GuitarData
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
