<template>
  <header>
      <div class="logo container">
          <img src="../assets/img/dc-logo.png" alt="">
      </div>
      <nav>
          <ul>
              <li v-for="(link, index) in links" :key="index"> <a @click="setActive(index)" :class="{'active': link.current}" :href="link.url">{{ link.text }}</a></li>
          </ul>
      </nav>
  </header>
</template>

<script>
export default {
    name: 'HeaderComp',

    data(){
    // i data nei template sono una funzione che restituisce un oggetto
    return{
      links:[
        {
          text:'CHARACTERS',
          url: 'javascript:void(0)',
          current: false
        },
        {
          text:'COMICS',
          url: 'javascript:void(0)',
          current: false
        },
        {
          text:'MOVIES',
          url: 'javascript:void(0)',
          current: false
        },
        {
          text:'TV',
          url: 'javascript:void(0)',
          current: false
        },
        {
          text:'GAMES',
          url: 'javascript:void(0)',
          current: false
        },
        {
          text: 'COLLECTIBLES',
          url: 'javascript:void(0)',
          current: false
        },
        {
          text: 'VIDEOS',
          url: 'javascript:void(0)',
          current: false
        },
        {
          text: 'FANS',
          url: 'javascript:void(0)',
          current: false
        },
        {
          text: 'NEWS',
          url: 'javascript:void(0)',
          current: false
        },
        {
          text: 'SHOP',
          url: 'javascript:void(0)',
          current: false
        }
      ]
    }
  },

  methods:{
    /* setActive(index){
      this.links.forEach((link) => {
        link.current = false;
      }
    } */

    setActive(index){
            this.links.forEach((link) => {
                link.current = false;
            })
            this.links[index].current = true;
        }
  }


}


</script>

<style lang="scss" scoped>

@import '../assets/style/vars.scss';

header{
    height: $height-100;
    width: 100vw;
    .logo{
        height: $height-100;
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
                    &:hover{
                        color: $dc-color;
                        padding-bottom: 40px;
                        border-bottom: 3px solid $dc-color;
                    }
                }
            }
        }
    }
}

.active{
    color: #0088FF;
    padding-bottom: 40px;
    border-bottom: 3px solid #0088FF;
}

</style>