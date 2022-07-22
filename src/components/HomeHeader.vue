
<template>
<div class="flex-header">
    <div>
        <figure>
            <img src="../assets/img/dc-logo.png" alt="">
        </figure>
    </div>
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
    margin:30px 50px;
}
.flex-menu{
    line-height: 100px;
}
.flex-menu , .flex-header{
    display: flex;
    justify-content: space-between;
}

</style>
