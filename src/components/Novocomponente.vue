<!--
    
    Lembrando que o component no Vue
    possui 3 elementos para inserir 
    1) Template


-->

<template>
    <!--Elemento que corresponde ao HTML-->
    <h1>{{ texto }}</h1>
    <!-- Estou definindo que texto vai ser atribuido a propriedade que foi definida dentro do elemento -->
    <!-- <p>{{ texto }}</p> -->
</template>

<script>
    //Elemento que compreende ao Javascript
    //Como nosso component está isolado temos que exportar ele
    export default {
        name: 'NovoComponenteVue',
        props: {
            texto: String
        }
    }
</script>


<style scoped>
    /*Elemento que compreende ao CSS*/
    h1{
        color: red
    }
    /*Scoped é para atribuir a folha de estilo somente a esse component*/
</style>