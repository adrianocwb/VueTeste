<template>
  <div id="app">

<Teste></Teste>

  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Teste from './components/teste.vue'

export default {
  name: 'app',
  components: {
    HelloWorld,
    Teste
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
