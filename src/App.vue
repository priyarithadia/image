<template>
  <div id="app">
    <upload></upload>
    
  </div>
</template>

<script>
import Upload from './components/Upload.vue'


export default {
  name: 'app',
  components: {
    Upload,
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
