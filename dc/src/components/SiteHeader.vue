<template>
<div>
    <div class="row">
    <img src="../assets/dc-logo.png" alt="">
    <ul>
        <li><a href="#">CHARACTERS</a></li>
        <li><a href="#">COMICS</a></li>
        <li><a href="#">MOVIES</a></li>
        <li><a href="#">TV</a></li>
        <li><a href="#">GAMES</a></li>
        <li><a href="#">COLLECTIBLES</a></li>
        <li><a href="#">VIDEOS</a></li>
        <li><a href="#">FANS</a></li>
        <li><a href="#">NEWS</a></li>
        <li><a href="#">SHOP</a></li>
    </ul>
    </div>
</div>
    
</template>
<script>
export default {
}
</script>

<style>
.row{
    display: flex;
    justify-content: space-between;
    width: 70%;
    margin: auto;
}
ul{
        list-style: none;
        display:flex;
        flex-direction: row;
        margin-top: 2.5rem;
        
        
}
a{
        text-decoration: none;
        padding: 0 1rem ;
        color:black;
        font-weight: bold;
}
</style>