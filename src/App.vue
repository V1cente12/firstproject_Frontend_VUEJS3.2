<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <MyCustomComponent />
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue';
import MyCustomComponent from './components/MyCustomComponent.vue'; // Importa el nuevo nombre

export default {
  name: 'App',
  components: {
    HelloWorld,
    MyCustomComponent // Usa el nuevo nombre aquí
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
