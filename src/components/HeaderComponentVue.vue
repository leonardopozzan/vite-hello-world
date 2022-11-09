<template>
    <header class="jumbo">
        <img src="/favicon.ico" class="logo">
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
    .logo{
        width: 10%;
    }
    .jumbo{
        height: 60vh;
        background-image: url('../../public/images/background.jpg');
        background-size: cover;
        background-position: center;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    .title{
        font-size: 2.5rem;
    }
</style>