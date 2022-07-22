<template>
<div class="container" id="DcComics">
  <HomeHeader/>
</div>

  
</template>

<script>
import HomeHeader from './components/HomeHeader.vue'

export default {
  name: 'DcComics',
  components: {
    HomeHeader,
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
