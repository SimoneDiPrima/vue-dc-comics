
<template>
<div class="flex-header">
    <div class="container">
        <figure>
            <a href=""><img src="../assets/img/dc-logo.png" alt=""></a>
        </figure>
        <div>
            <nav>
                <ul class="flex-menu">
                    <li v-for="link in links" :key="link.text">
                        <a :href="link.url" 
                        :class="{ current : link.current}"  >
                        {{ link.text }}
                        </a>
                    </li>
                </ul>
            </nav>
        </div>
    </div>
</div>
</template>

<script>
export default{
     name: 'HomeHeader',
      currentIndex : 0,
     data(){
        return{
        links:[
  {
    text: 'Characters',
    url: '#',
    current: false,
  },
  {
    text: 'Comics',
    url: '#',
    current: true,
  },
  {
    text: 'Movies',
    url: '#',
    current: false,
  },
  {
    text: 'TV',
    url: '#',
    current: false,
  },
  {
    text: 'Games',
    url: '#',
    current: false,
  },
  {
    text: 'Collectibles',
    url: '#',
    current: false,
  },
  {
    text: 'Videos',
    url: '#',
    current: false,
  },
  {
    text: 'Fans',
    url: '#',
    current: false,
  },
  {
    text: 'News',
    url: '#',
    current: false,
  },
  {
    text: 'Shop',
    url: '#',
    current: false,
  },
]
    }
     }
}
</script>

<style lang="scss" scoped>
.flex-header{
    height: 200px;
    margin-top:30px;
    .flex-menu{
    line-height: 100px;
    display:flex;
}
li a{
    text-decoration: none;
    color:darkslategray;
    font-weight: bold;
    padding:5px;
    &.current,
    &:hover{
        text-decoration: underline dodgerblue;
        color:dodgerblue
    }
    
    }
}

</style>
