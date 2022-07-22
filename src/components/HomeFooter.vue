<template>
<footer>
    <div class="top-footer">
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
    <div class="down-footer">
      
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
    height:500px;
   max-width:100vw;
   position:relative;
   display:flex;
   justify-content:space-between;
   padding:30px;
   
}
.down-footer{
height:150px;
max-width:100vw;
background-color: slategray;
position:absolute;
left:0;
right:0;
top:150%;
}
img{
    margin-top:-20px;
    width:100%;
    height:auto;
    text-align:center;
}
.footer-menu{
    display:flex;
}
.footer-menu li a{
    line-height: 150%;
    color:white;
    font-weight: lighter;
}

.title-footer-menu{
    color:white;
    margin-top:10px;
}


</style>