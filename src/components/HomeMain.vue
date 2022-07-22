<template>
<main id="main">
    <div>
     <h4> --<i class="fa-solid fa-angle-right arrow"></i> contents goes here <i class="fa-solid fa-angle-left arrow"></i>--  </h4>
    </div>
</main>

</template>

<script>
export default{
     name: 'HomeMain',
}

</script>

<style>

#main{
    height:250px;
   max-width:100vw;
    color:white;
    background-color: black;
    font-size: 1.5rem;
}
#main h4{
 padding-top:30px;
   margin-left:30px;
}
.arrow{
    font-size:60%;
}

</style>