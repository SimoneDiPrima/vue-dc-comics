
<template>
<div class="flex-header">
    <div class="container">
        <figure>
            <a href=""><img src="../assets/img/dc-logo.png" alt=""></a>
        </figure>
        <div>
            <nav>
                <ul class="flex-menu">
                    <li><a href="">CHARACTERS</a></li>
                    <li><a href="">COMICS</a></li>
                    <li><a href="">MOVIES</a></li>
                    <li><a href="">TV</a></li>
                    <li><a href="">GAMES</a></li>
                    <li><a href="">COLLECTIBLES</a></li>
                    <li><a href="">VIDEO</a></li>
                    <li><a href="">FANS</a></li>
                    <li><a href="">NEWS</a></li>
                    <li><a href="">SHOP</a></li>
                </ul>
            </nav>
        </div>
    </div>
</div>
</template>

<script>
export default{
     name: 'HomeHeader',
}
</script>

<style>
li a{
    text-decoration: none;
    color:darkslategray;
    font-weight: bold;
    padding:5px;
}
.flex-header{
    height: 200px;
    margin-top:30px;
}
.container{
  margin: 0 auto;
  max-width:1200px;
  display: flex;
    justify-content: space-between;
}
.flex-menu{
    line-height: 100px;
    display:flex;
    
}

</style>
