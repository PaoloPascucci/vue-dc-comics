<template>
<div class="container2">
    <div class="">
        <button type="submit">SIGN-UP NOW!</button>
    </div>
    <div class="left">
        <span class="follow">FOLLOW US</span>
        <img src="../assets/footer-facebook.png" alt="">
        <img src="../assets/footer-twitter.png" alt="">
        <img src="../assets/footer-youtube.png" alt="">
        <img src="../assets/footer-pinterest.png" alt="">
        <img src="../assets/footer-periscope.png" alt="">
    </div>
</div>
    
</template>
<script>
export default {
}
</script>

<style lang="scss">
.container2{
    display: flex;
    justify-content: space-around;
    background-color:#303030 ;
    padding: 1.63rem ;
    button{
        border: #0282f9 1px solid ;
        background-color: #303030;
        color:white;
        padding: 1rem;
        font-weight: bold;
    }
    .follow{
            vertical-align: 10px;
            font-weight: bold;
            color: #0282f9;
        }
    }
        img{
            padding: 0 1rem;
        }

</style>