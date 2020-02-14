<template>
  <div id="app">
    <Segundos />
    <Contador />
  </div>
</template>

<script>
import Segundos from './components/Segundos.vue'
import Contador from './components/Contador.vue'

export default {
  name: 'App',
  components: {
    Segundos,
    Contador
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
  background-color: #2c3e50;
  padding: 2em;
  
}
#card{
  background-color: ivory;
}

</style>
