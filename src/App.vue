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

<style>
*{
margin:0;
padding:0;
box-sizing: border-box;
}
.container{
  margin: 0 auto;
  max-width:1200px;
}
img{
  height:auto;
  max-width: 100%;
}
ul{
  list-style-type:none;
}
</style>
