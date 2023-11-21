<template>
  <div id="app">
    <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
    <!-- 3) Utilizar o component -->
    <NovoComponenteVue texto="Essa é a diretiva conhecida como v-text, permite a apresentação de textos, tal como ocorrido quando usamos diretivas diretas"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
// 1) Importa o componente
import NovoComponenteVue from './components/Novocomponente.vue'

export default {
  name: 'App',
  components: {
    HelloWorld,
    // 2) Declarar o component
    NovoComponenteVue,
    
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
