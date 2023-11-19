<!--
    
    Lembrando que o component no Vue
    possui 3 elementos para inserir 
    1) Template


-->

<template>
    <!--Elemento que corresponde ao HTML-->
    <h1>Bem vindo ao meu App Vue</h1>
</template>

<script>
    //Elemento que compreende ao Javascript
    //Como nosso component está isolado temos que exportar ele
    export default {
        name: 'Newcomponent.vue',
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