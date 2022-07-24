<template>
<div id="DcComics">
  
  <HomeHeader/>
  <HomeMain/>
  <HomeFooter/>
</div>

  
</template>

<script>
import HomeHeader from './components/HomeHeader.vue'
import HomeMain from './components/HomeMain.vue'
import HomeFooter from './components/HomeFooter.vue'


export default {
  name: 'DcComics',
  components: {
    HomeHeader,
    HomeMain,
    HomeFooter
  }
}
</script>

<style lang="scss">
@import './assets/sass/style.scss';
</style>
