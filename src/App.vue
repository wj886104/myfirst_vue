<template>
  <div id="app">
    <router-view/>
    <FooterGuider v-show="$route.meta.showFooter" />
  </div>
</template>

<script>
  import  FooterGuider from './conmponents/FooterGuider/FooterGuider.vue'
    export default {
    components:{
      FooterGuider
    }
  }
</script>


<style lang="stylus" rel="stylesheet/stylus">
  #app
    width 100%
    height 100%
    background #f5f5f5


</style>
