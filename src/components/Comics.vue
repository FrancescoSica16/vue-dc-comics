<template>
    <div class="comic-item">
        <img :src="image" :alt="title">
        <h4> {{ title }} </h4>        
    </div>
</template>

<script>
    export default {
        name:"Comics",
        props: ['title','image'],
    }
</script>

<style lang="scss" scoped>
 @import "../style/variabiles.scss";
    .comic-item{
        
        flex-basis: calc(100% / 6 - 24px ); // da chiarire il funzionamento 
        
           
        margin: 6px;

        img {
            width: 100%;
            aspect-ratio: 1 / 1;
            object-fit: cover;
            object-position: top;
            margin-bottom: 10px;
        }

        h4{
           
            text-transform: uppercase;
            font-family: $mainFont;
            font-size: 0.7rem;
            font-weight: 500;
            color: $itemComicTitle;
        }
    }
</style>