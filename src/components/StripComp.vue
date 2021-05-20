<template>
  <div class="container">
      <ul>
          <li><img src="../assets/img/buy-comics-digital-comics.png" alt="" srcset=""> <span> DIGITAL COMICS</span></li>
          <li><img src="../assets/img/buy-comics-merchandise.png" alt=""><span>DC MERCHANDISE</span></li>
          <li><img src="../assets/img/buy-comics-subscriptions.png" alt=""><span>SUBSCRIPTION</span></li>
          <li><img src="../assets/img/buy-comics-shop-locator.png" alt=""><span>COMIC SHOP LOCATOR</span></li>
          <li><img src="../assets/img/buy-dc-power-visa.svg" alt=""><span>DC POWER VISA</span></li>
      </ul>
  </div>
</template>

<script>
export default {
    name: 'StripComp'
}
</script>

<style lang="scss" scoped>

@import '../assets/style/vars.scss';

    div{
        height: 120px;
        width: 100%;
        background-color: $dc-color;
        ul{    
            display: flex;
            li{
                line-height: 120px;
                display: flex;
                align-items: center;
                padding: 0px 40px; 
                img{
                    height: 35px;
                    
                }
                span{
                    color: white;
                    font-size: 0.7rem;
                    padding-left: 10px;
                }
            }
        }
    }
</style>