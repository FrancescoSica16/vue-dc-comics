<template>
  <div id="main-block">
    <div id="main-wrapper" class="container">

    <Comics v-for="(comic, index) in ComicsData" :key="index" :title="comic.series" :image="comic.thumb"/>

    </div>
  </div>
</template>

<script>

import Comics from "./Comics.vue";
import ComicsData from "../data/ComicsData.js";
export default {
  name: 'Products',
 
  components: {
    Comics,
  },
  data: function(){
    return{ 
      ComicsData,
    }
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
    justify-content: center;
    margin: 0 auto;
    padding: 40px 0;

    & h2{
      padding: 50px 0px;
      color: white;
      font-family: $mainFont;
      
    }
  }

  

</style>