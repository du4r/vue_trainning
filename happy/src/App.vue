<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Bem vindo ao HappY"/>
  </div>
</template>

<script>
import msg from './components/main.vue'

export default {
  name: 'App',
  components: {
    msg
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
  background-color:whitesmoke;
}
#app img {
  width: 150px;
  height: 150px;
}
</style>
