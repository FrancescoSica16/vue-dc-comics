<template>
  <div id="main-block">
    <div id="main-wrapper" class="container">
        <h2>Content main section</h2>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Main',
  
}
</script>

<style scoped lang="scss">
@import "../style/variabiles.scss";
#main-block{
  background-color: black;
}
#main-wrapper{
  background-color: black;
  height: 200px;
   margin: 0 auto;

  & h2{
    padding: 50px 0px;
    color: white;
    font-family: $mainFont;
    
  }
}

</style>