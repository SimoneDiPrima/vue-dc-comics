<template>
<footer>
    
    <div class="top-footer">
        <div class="container">
            <div class="footer-menu">
                <div class="col">
                        <h4 class="title-footer-menu">DC COMICS</h4>
                    <ul>
                        <li><a href="">terms of use</a></li>
                        <li><a href="">privacy policy</a></li>
                        <li><a href="">Ad choiches</a></li>
                        <li><a href="">Advertising</a></li>
                        <li><a href="">Jobs</a></li>
                        <li><a href="">Subscription</a></li>
                        <li><a href="">Talent Workshop</a></li>
                        <li><a href="">CPSC certificates</a></li>
                        <li><a href="">Ratings</a></li>
                    </ul>
                    <h4 class="title-footer-menu">SHOP</h4>
                    <ul>
                        <li><a href="">shop dc</a></li>
                        <li><a href="">shop dc collectibles</a></li>
                    </ul>
                </div>
                <div class="col">
                    <h4 class="title-footer-menu">DC</h4>
                    <ul>
                        <li><a href="">terms of use</a></li>
                        <li><a href="">privacy policy</a></li>
                        <li><a href="">Ad choiches</a></li>
                        <li><a href="">Advertising</a></li>
                        <li><a href="">Jobs</a></li>
                        <li><a href="">Subscription</a></li>
                        <li><a href="">Talent Workshop</a></li>
                        <li><a href="">CPSC certificates</a></li>
                        <li><a href="">Ratings</a></li>
                        <li><a href="">Shop help</a></li>
                        <li><a href="">Contact us</a></li>
                    </ul>
                </div>
                <div class="col">
                    <h3 class="title-footer-menu">SITES</h3>
                        <ul>
                            <li><a href="">DC</a></li>
                            <li><a href="">MAD Magazine</a></li>
                            <li><a href="">DC Kids</a></li>
                            <li><a href="">DC Universe</a></li>
                            <li><a href="">DC Power Visa</a></li>
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
                    <li class="followus"><a href="">FOLLOW US</a></li>
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
}


</script>

<style>

.top-footer{
    background-image: url("../assets/img/footer-bg.jpg");
    height:400px;
   max-width:100vw;
   position:relative;
   padding:30px;  
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
top:135%;
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

</style>