<template>
    <main>
        <h2 class="sub-title">{{titolo}}</h2>
        <div class="text">
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Natus iure illum dignissimos! Non nostrum quibusdam, quisquam pariatur autem rerum sed iure quo facilis quam sequi error excepturi cumque, voluptatem nesciunt.s
        </div>
    </main>
</template>

<script>
    export default {
        data(){
            return{
                titolo: 'Descrizione dell\'applicazione'
            }
        }
    }
</script>

<style lang="css" scoped>
    .sub-title{
        color: blue;
        text-align: center;
    }
    .text{
        background-color: lightgrey;
        width: 80%;
        margin: auto;
    }

</style>