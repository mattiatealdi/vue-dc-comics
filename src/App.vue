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

@import 'assets/style/general.scss';

</style>
