<template>
  <div class="comic-item">
        <h2>Content main section</h2>
      </div>
</template>

<script>
    export default {

    }
</script>

<style lang="scss" scoped>
    .comic-item{
        flex-basis: calc(100% / 6 - 18px); // da chiarire il funzionamento
        height: 200px;
        background-color: blueviolet;
        border: 1px solid black;
        margin: 3px;
    }
</style>