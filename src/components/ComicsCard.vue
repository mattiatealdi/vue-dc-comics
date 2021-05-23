<template>
  <div class="card">
      <img :src="card.thumb" :alt="card.type">
      <span>{{ card.series }}</span>
  </div>
</template>

<script>
export default {
    name:'ComicsCard',
    props:{
        card:Object
    }
}
</script>

<style lang="scss" scoped>
    .card{
        width: calc(100% / 6);
        padding: 0px 10px;
        margin-top: 40px;
        img{
            width: 80%;
            overflow: hidden;
        }
        span{
            font-size: 15px;
            display: block;
            margin-top: -5px;
            padding-bottom: 10px;
        }
    }
</style>