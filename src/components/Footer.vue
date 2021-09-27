<template>
  <footer>
    <div id="footer-container">

      <div id="footer-nav-wrapper">
        <div class="nav-column">         
          <nav>
            <h4>Dc Comics</h4>
            <ul>
              <li>
                <a href="#">Characters</a>
              </li>
              <li>
                <a href="#" class="active">Comics</a>
              </li>
              <li>
                <a href="#">Movies</a>
              </li>
              <li>
                <a href="#">TV</a>
              </li>
              <li>
                <a href="#">Games</a>
              </li>
              <li>
                <a href="#">Video</a>
              </li>
                <li>
                <a href="#">News</a>
              </li>       
            </ul>
          </nav>
        </div>  
        <div class="nav-column">         
          <nav>
            <h4>DC</h4>
            <ul>
              <li>
                <a href="#">Term of use</a>
              </li>
              <li>
                <a href="#" class="active">Privacy Policy (New)</a>
              </li>
              <li>
                <a href="#">Ad Choices</a>
              </li>
              <li>
                <a href="#">Advertising</a>
              </li>
              <li>
                <a href="#">Jobs</a>
              </li>
              <li>
                <a href="#">Subscriptions</a>
              </li>
                <li>
                <a href="#">CPSC Certificates</a>
              </li> 
              <li>
                <a href="#">Ratings</a>
              </li>
              <li>
                <a href="#">Shop Help</a>
              </li>
                <li>
                <a href="#">Contact Us</a>
              </li>        
            </ul>
          </nav>
        </div> 
        <div class="nav-column">
          
          <nav>
            <h4>Sites</h4>
            <ul>
              <li>
                <a href="#">DC</a>
              </li>
              <li>
                <a href="#" class="active">DC UNIVERSE INFINITE</a>
              </li>
              <li>
                <a href="#">DC Kids</a>
              </li>
              <li>
                <a href="#">DC Shop</a>
              </li>
              <li>
                <a href="#">MAD Magazine</a>
              </li>
            </ul>
          </nav>
        </div>
         <div class="nav-column">         
          <nav>
            <h4>Shop</h4>
            <ul>
              <li>
                <a href="#">Shop DC</a>
              </li>
              <li>
                <a href="#" class="active">Shop DC Collectibles</a>
              </li>              
            </ul>
          </nav>
        </div>
           
      </div>

      <a href="#">
        <img src="../assets/img/dc-logo-bg.png" alt="">
      </a>

    </div>

    <div id="social-footer">

    </div>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  
}
</script>

<style scoped lang="scss">
@import "../style/variabiles.scss";

footer{
  height: 350px;
  background: url(../assets/img/footer-bg.jpg);
}

#footer-container{
  width: 1000px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;

  & #footer-nav-wrapper{
    height: 350px;
    width: 400px;
    padding-top: 20px;
    display: flex;
    align-items: flex-start;
    flex-wrap: wrap;
   
    
  }

   & img {
     object-fit: cover; 
     width: 450px;
     height: 350px;
     display: flex;
   }
}

.nav-column{
  display: inline-block;
  padding:0 20px 20px 0px;

  h4{
    color: $titleNavColor;
    font-family: $footerFont;
    text-transform: uppercase;
  }

  & ul{
    list-style: none;
    
    padding-left: 0;
  }

  & li a{
    text-decoration: none;
    color: $linkNavColor;
    font-size: 0.7rem;
    font-family: $footerFont;
    
    
  }
}
</style>