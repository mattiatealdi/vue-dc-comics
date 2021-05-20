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
        <div class="logo-footer">

        </div>
        

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
            
        .logo-footer{
            float:right;
            width: 40%;
            height: 100%;
            margin: 0px 200px 0px 0;
            /* margin: */
            background-image: url('../assets/img/dc-logo-bg.png');
            background-repeat: no-repeat;
            background-size: cover;
        }

       }

       .footer-bottom{
           height: 100px;
           background-color: #303030;

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

           .container-right{
               width: 50%;
               height: 100%;
               float:right;
               ul{
                   display: flex;
                   margin-left: 50px;
                   
                   li{
                       padding: 30px 10px;
                       font-size: 0.75rem;
                       img{
                           width: 30px;
                       }
                       h3{
                           padding-top: 10px;
                           color: #0088FF;
                       }
                   }
               }
           }
       }
    }
</style>