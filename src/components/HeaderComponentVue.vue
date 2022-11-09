<template>
    <header>
        <h1 class="title">{{titolo}}</h1>
    </header>
</template>

<script>
    export default {
        data(){
            return{
                titolo: 'La mia prima App con Vite'
            }
        }
    }
</script>

<style lang="css" scoped>
    header{
        height: 60vh;
        background-color: aqua;
        display: flex;
        align-items: center;
        justify-content: center;
    }
    .title{
        color: white;
        padding: 10px;
        background-color: red;
    }
</style>