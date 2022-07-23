<template>
<footer>
    <div class="top-footer">
        <div class="container">
            <div class="footer-menu">
                <div class="col">
                        <h4 class="title-footer-menu">DC COMICS</h4>
                    <ul>
                        <li v-for="link in links" :key="link.text" ><a :href="link.url">{{ link.text }}</a></li>
                    </ul>
                    <h4 class="title-footer-menu">SHOP</h4>
                    <ul>
                         <li v-for="link in FooterShopMenu" :key="link.text"><a href="#">{{ link.text }}</a></li>
                    </ul>
                </div>
                <div class="col">
                    <h4 class="title-footer-menu">DC</h4>
                    <ul>
                          <li v-for="link in FooterTopMenu" :key="link.text"><a href="#">{{ link.text }}</a></li>
                    </ul>
                </div>
                <div class="col">
                    <h3 class="title-footer-menu">SITES</h3>
                        <ul>
                            <li v-for="website in website" :key="website.text"><a :href="website.url">{{ website.text }}</a></li>
                           
                        </ul>
                </div>
            </div>
            <figure>
                <img src="../assets/img/dc-logo-bg.png" alt="">
            </figure>
        </div>
    </div>
    <div class="down-footer">
        <div class="container">
            <div><button class="button-footer">SIGN UP NOW!</button></div>
            <div>
                <ul class="footer-menu">
                    <li id="followus"><a href="">FOLLOW US</a></li>
                    <li class="socialFooter-list"><a href=""><img src="../assets/img/footer-twitter.png" alt=""></a></li>
                    <li class="socialFooter-list"><a href=""><img src="../assets/img/footer-youtube.png" alt=""></a></li>
                    <li class="socialFooter-list"><a href=""><img src="../assets/img/footer-facebook.png" alt=""></a></li>
                    <li class="socialFooter-list"><a href=""><img src="../assets/img/footer-periscope.png" alt=""></a></li>
                    <li class="socialFooter-list"><a href=""><img src="../assets/img/footer-pinterest.png" alt=""></a></li>
                </ul>
        
            </div>
        </div>
    </div>
</footer>
</template>

<script>
export default{
     name: 'HomeFooter',
     data(){
        return{
     FooterTopMenu : [ {
    text: 'terms of use',
    url: '#',
    current: false,
  },
  {
    text: 'privacy policy',
    url: '#',
    current: true,
  },
  {
    text: 'Ad choiches',
    url: '#',
    current: false,
  },
  {
    text: 'Advertising',
    url: '#',
    current: false,
  },
  {
    text: 'Job',
    url: '#',
    current: false,
  },
  {
    text: 'Subscription',
    url: '#',
    current: false,
  },
  {
    text: 'Talent Workshop',
    url: '#',
    current: false,
  },
  {
    text: 'CPSC certificates',
    url: '#',
    current: false,
  },
  {
    text: 'Rating',
    url: '#',
    current: false,
  },
  {
    text: 'Shop Help',
    url: '#',
    current: false,
  },
  {
    text: 'Shop Help',
    url: '#',
    current: false,
  },
  {
    text: 'contact us',
    url: '#',
    current: false,
  }
  
  
],
FooterShopMenu:[{text: 'shop dc',
    url: '#',
    current: false},
    {text: 'shop dc collectibles',
    url: '#',
    current: false},
    ],
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
  }],
    website:[
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
  }],
}}}
</script>

<style>

.top-footer{
    background-image: url("../assets/img/footer-bg.jpg");
    height:500px;
   max-width:100vw;
   position:relative;
   padding:30px;  
}
.top-footer ul li,
.top-footer ul li h4{
    margin-right:10px;
}
.top-footer ul li a,
.down-footer ul li a
{
    text-decoration:none;
}
.container{
  margin: 0 auto;
  max-width:1200px;
  display: flex;
    justify-content: space-between;
}
.down-footer{
min-height:150px;
max-width:100vw;
background-color: rgb(58, 49, 49);
position:absolute;
left:0;
right:0;
top:150%;
line-height:150px;

}
.flex-footer-bottom{
    display:flex;
    justify-content: space-between;
}
img{
    margin-top:-20px;
    max-width:100%;
    height:auto;
    text-align:center;
}
.footer-menu{
    display:flex;
}
.footer-menu li a{
    line-height: 150%;
    color:lightgrey;
    font-weight: lighter;
}

.title-footer-menu{
    color:white;
    margin-top:10px;
}

.socialFooter-list{
    padding:8px; 
    color:slategray
}
.button-footer{
    padding:5px;
    font-size: 20px;
    color:white;
    background-color: rgb(58, 49, 49);
    border:1px solid dodgerblue;
}
#followus a{
    color:dodgerblue;
}

</style>