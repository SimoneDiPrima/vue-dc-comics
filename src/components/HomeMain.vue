<template>
<main id="main">
    
    <ComicsCards/>
</main>

</template>

<script>
import ComicsCards from './ComicsCards.vue';
export default{
     name: 'HomeMain',
    components:{
    ComicsCards
}
}

</script>

<style lang="scss">
#main{
    height:800px;
   max-width:100vw;
    color:white;
    background-color: black;
    font-size: 1.5rem;
    .container{
      margin: 0 auto;
      max-width:1200px;
      display:flex;
      flex-wrap:wrap;
    }
    }
</style>