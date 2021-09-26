<template>
  <header class="container">
    <a href="#" class="header-logo">
      <img src="../assets/img/dc-logo.png" alt="">
    </a>
    <nav>
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
          <a href="#">collectibles</a>
        </li>
        <li>
          <a href="#">Video</a>
        </li>
        <li>
          <a href="#">Fans</a>
        </li>
          <li>
          <a href="#">News</a>
        </li>
        <li>
          <a href="#">Shop</a>
        </li>
      </ul>
    </nav>

  </header>
</template>

<script>
export default {
  name: 'Header',

  data: function () {
    return {
      // qui scriviamo quello che scriveremo nel data
      index:0,
      links:[
        {
          text: "Characters",
          url: "#",
          current: false,
        },
         {
          text: "Comics",
          url: "#",
          current: false,
        },
         {
          text: "Movies",
          url: "#",
          current: false,
        },
         {
          text: "TV",
          url: "#",
          current: false,
        },
         {
          text: "Games",
          url: "#",
          current: false,
        },
         {
          text: "collectibles",
          url: "#",
          current: false,
        },
         {
          text: "Video",
          url: "#",
          current: false,
        },
         {
          text: "Fans",
          url: "#",
          current: false,
        },
         {
          text: "News",
          url: "#",
          current: false,
        },
         {
          text: "Shop",
          url: "#",

          current: false,
        },

      ]
    }
 },

 methods:{

 }
  
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../style/variabiles.scss";

header{
  
  height: 80px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 0 auto;
}

header img{
  height: 50px;
}

ul{
  display: flex;
  list-style: none;
  text-decoration: none;
}
li {
  line-height: 76px;
}
li a{
  display: inline-block;
  margin: 0px 15px;

  text-decoration: none;
  font-family: $navFont;
  font-weight: 500;
  font-size: 0.7rem;
  color: $navFontColor;
  text-transform: uppercase;

  &.active{
    border-bottom: 4px solid rgb(12, 124, 236);
    color:rgb(12, 124, 236) ;
  }

  &:hover{
    color : darken(rgb(12, 124, 236), 5%);
  }
}

</style>
