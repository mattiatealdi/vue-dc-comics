<template>
  <header>
      <div class="logo container">
          <img src="../assets/img/dc-logo.png" alt="">
      </div>
      <nav>
          <ul>
              <li><a href="#">CHARACTERS</a></li>
              <li><a href="#">COMICS</a></li>
              <li><a href="#">MOVIES</a></li>
              <li><a href="#">TV</a></li>
              <li><a href="#">GAMES</a></li>
              <li><a href="#">COLLECTIBLES</a></li>
              <li><a href="#">VIDEOS</a></li>
              <li><a href="#">FANS</a></li>
              <li><a href="#">NEWS</a></li>
              <li><a href="#">SHOP</a></li>
          </ul>
      </nav>
  </header>
</template>

<script>
export default {
    name: 'HeaderComp',
}
</script>

<style lang="scss" scoped>

header{
    height: 100px;
    width: 100vw;
    .logo{
        height: 100px;
        float:left;
        img{
            width: 80px;
            margin: 10px 0px 10px 0;
        }
        
    }
    nav{
        float:left;
        ul{
            display: flex;
            line-height: 100px;
            li{
                padding: 0 10px;
                a{
                    font-size: 0.7rem;
                    color: #1B2D3C;
                }
            }
        }
    }
}

</style>