<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <!-- 3) Utilizar o component -->
    <NewComponent texto="Este é o texto para o parágrafo"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import NewComponent from './components/NewComponent.vue';
// 1) Importa o componente
import NewComponent from './components/NewComponent.vue';

export default {
  name: 'App',
  components: {
    HelloWorld,
    // 2) Declarar o component
    NewComponent,
    NewComponent
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
