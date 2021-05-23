<template>
  <main>
      <div class="wrapper-jumbotron">
      </div>
      <div class="comics-container">
          <div class="wrapper flex">
              <ComicsCard 
                v-for="(comic, index) in comics"
                :key= "index"
                :card="comic"
              />
          </div>
      </div>
  </main>
</template>

<script>
import comics from "@/assets/data/dc-comics.js";
import ComicsCard from '@/components/ComicsCard';

export default {
    name: 'MainComp',

    components:{
        ComicsCard
    },

    data(){
        return{
            comics
        }
    },

    methods:{
        
    },

    mounted(){
        //console.log(comics);
    }
}
</script>

<style lang="scss" scoped>
@import '../assets/style/vars.scss';
@import '../assets/style/general.scss';

    main{
        background-color: #1C1C1C;
        /* height: 100px; */ // HERE TO CHANGE MAIN DIMENSIONS
        width: 100%;
        .wrapper-jumbotron{
            height:300px;
            background-image: url('../assets/img/jumbotron.jpg');
            background-size: cover;
        }

        .comics-container{
            background-color: #1C1C1C;
            /* height: 1000px; */
        }

        
        div{
            color: white;
            /* line-height: 100px; */ // WHILE CHANGING MAIN DIMENSIONS DISCARD THIS LINE
            font-size: 2rem;
        }
    }

</style>