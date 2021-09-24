<template>
<div id="footer-wrapper">
  <footer class="container">
    <img src="../assets/img/dc-logo-bg.png" alt="">
  </footer>
  <div id="social-footer">

  </div>
</div>  
</template>

<script>
export default {
  name: 'Footer',
  
}
</script>

<style scoped lang="scss">
@import "../style/variabiles.scss";

#footer-wrapper{
  height: 350px;
  background: url(../assets/img/footer-bg.jpg);
}

footer{
height: 350px;
margin: 0 auto;
   & img{
    float: right;
    object-fit: cover; 
    width: 450px;
    height: 350px;
    
  }
}

#social-footer{
  height: 60px;
  background-color: $socialFooterColor;
}

</style>