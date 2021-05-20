<template>
  <footer>
    <div class="footer-top">
        <div class="container">
            <ul>
                <li><h3>DC COMICS</h3></li>
                <li>Characters</li>
                <li>Comics</li>
                <li>Movies</li>
                <li>TV</li>
                <li>Games</li>
                <li>Videos</li>
                <li>News</li>
                <li><h3>SHOP</h3></li>
                <li>Shop DC</li>
                <li>Shop DC collectibles</li>
            </ul>
            <ul>
                <li><h3>DC</h3></li>
                <li>Terms of use</li>
                <li>Privacy Policy</li>
                <li>Ad choices</li>
                <li>Advertising</li>
                <li>Jobs</li>
                <li>Subscriptions</li>
                <li>Talent workshops</li>
                <li>CPSC Certificates</li>
                <li>Ratings</li>
                <li>Shop help</li>
                <li>About us</li>
            </ul>
            <ul>
                <li><h3>SITES</h3></li>
                <li>DC</li>
                <li>Mad magazine</li>
                <li>DC Kids</li>
                <li>DC Universe</li>
                <li>DC Power Visa</li>
            </ul>
        </div>

        <img src="../assets/img/dc-logo-bg.png" alt="">

    </div>
    <div class="footer-bottom">
        <div class="container">
            <button class="sign">
                SIGN-UP NOW!
            </button>
        </div>

        <div class="container-right">
            <ul>
            <li><h3>FOLLOW US</h3></li>
            <li><img src="../assets/img/footer-facebook.png" alt=""></li>
            <li><img src="../assets/img/footer-twitter.png" alt=""></li>
            <li><img src="../assets/img/footer-youtube.png" alt=""></li>
            <li><img src="../assets/img/footer-pinterest.png" alt=""></li>
            <li><img src="../assets/img/footer-periscope.png" alt=""></li>
        </ul>
        </div>
    </div>
  </footer>
</template>

<script>
export default {
    name: 'FooterComp',
}
</script>

<style lang="scss" scoped>
    footer{
        
       .footer-top{
        height: 400px;
        background-image: url(../assets/img/footer-bg.jpg);

        .container{
            float: left;
            display: flex;
            ul{
                padding: 0 15px;
            li{
                color: #818383;
                font-size: 0.75rem;
                padding: 3px 0;
                h3{
                color: white;
                padding: 25px 0;
                }
            }
            }
        }
            
        img{
            float:right;
            width: 35%;
            margin: -40px 200px 0 0;
            z-index: 0;
            
        }

       }

       .footer-bottom{
           height: 100px;
           background-color: #303030;
           z-index: 999;

           .container{
               float:left;
           }

           .sign{
               background-color: #303030;
               border: 1px solid #0088FF;
               padding: 10px;
               margin-top: 25px;
               color: white;
           }

           .right-container{
               width: 50%;
               background:red;
               height: 100%;
               float:right;
           }
       }
    }
</style>