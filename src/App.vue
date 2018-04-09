<template>
  <div id="app">
    <img src="./assets/logo.png">
    <UpLoad :files="files"></UpLoad>
  </div>
</template>

<script>
import UpLoad from './components/upload'

export default {
  name: 'App',
  data () {
    return {
      files: [{text: '1.png'}]
    }
  },
  components: {
    UpLoad
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
