<template>
    <div class="comic-item">

        <img :src="image" :alt="title">
        <h2> {{ title }} </h2>
        
    </div>
</template>

<script>
    export default {
        name:"Comics",
        prop: ['title','image'],
    }
</script>

<style lang="scss" scoped>
    .comic-item{
        flex-basis: calc(100% / 6 - 18px); // da chiarire il funzionamento
        height: 150px;
        background-color: blueviolet;
        border: 1px solid black;
        margin: 3px;
    }
</style>