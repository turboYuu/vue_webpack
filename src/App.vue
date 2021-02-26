<template>
  <div id="app">
    <img src="https://ss3.bdstatic.com/70cFv8Sh_Q1YnxGkpoWK1HF6hhy/it/u=3118799085,3545635564&fm=26&gp=0.jpg" alt="">
    <h1>LESS is MORE</h1>
    <h1>iPhone</h1>
    <h1>Mac</h1>
    <h1>IOS</h1>
    <h1>Music</h1>
    <h1>Watch</h1>
    <!-- <img src="./assets/logo.png">
    <HelloWorld/> -->
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
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
