<template>
  <div id="main-block">
    <div id="main-wrapper" class="container">
    <Comics/>
    <Comics/>
    <Comics/>
    <Comics/>
    <Comics/>
    <Comics/>
    <Comics/>
    <Comics/>
    <Comics/>
    <Comics/>
    <Comics/>
    <Comics/>

    
    </div>
  </div>
</template>

<script>

import Comics from "./Comics.vue";

export default {
  name: 'Products',
  components: {
    Comics,
  }
  
}
</script>

<style scoped lang="scss">
  @import "../style/variabiles.scss";
  #main-block{
    background-color: black;
  }
  #main-wrapper{
    background-color: black;
    display: flex;
    flex-wrap: wrap;
    
    margin: 0 auto;

    & h2{
      padding: 50px 0px;
      color: white;
      font-family: $mainFont;
      
    }
  }

  

</style>