<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <Bemvindo msg="Bem vindo a Escola Estadual Arthur Ramos"/>
  </div>
</template>

<script>
import Bemvindo from './components/Bemvindo.vue'

export default {
  name: 'App',
  components: {
    Bemvindo
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
