<template>
  <img alt="Vue logo" src="./assets/logo.png">
  <ListaQueHaceres></ListaQueHaceres>
</template>

<script>
//import HelloWorld from './components/HelloWorld.vue'
import ListaQueHaceres from './components/ListaQueHaceres.vue'

export default {
  name: 'App',
  components: {
    //HelloWorld
    ListaQueHaceres
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
