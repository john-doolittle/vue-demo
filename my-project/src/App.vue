<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <h3>Yo watup</h3>
    <CounterBtn/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import CounterBtn from './components/CounterBtn.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    CounterBtn
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
