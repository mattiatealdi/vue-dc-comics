<template>
  <div id="app">

    <header-comp />

    <main-comp />

    <strip-comp />

    <footer-comp />
  
  </div>
</template>

<script>
import FooterComp from './components/FooterComp.vue'
import HeaderComp from './components/HeaderComp.vue'
import MainComp from './components/MainComp.vue'
import StripComp from './components/StripComp.vue'

export default {
  name: 'App',
  components: {
    HeaderComp,
    MainComp,
    StripComp,
    FooterComp
  }
}
</script>

<style lang="scss">
#app {
  
}

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

ul{
  list-style-type: none;
}

a{
  text-decoration: none;
}

.container{
  width: 40%;
  padding-left: 200px;
}

.wrapper{
  width: 80%;
  margin: 0 auto;
}

</style>
