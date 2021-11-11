<template>
<div>
    <section class="first">
        <div>Content goes here</div>
    </section>
    <section class="second">
        <div class="container">
            <div class="object">
                <img src="../assets/buy-comics-digital-comics.png" alt="">
                <span>DIGITAL COMICS</span>
            </div>
            <div class="object">
                <img src="../assets/buy-comics-merchandise.png" alt="">
                <span>DC MERCHANDISE</span>
            </div>
            <div class="object">
                <img src="../assets/buy-comics-subscriptions.png" alt="">
                <span>SUBSCRIPTION</span>
            </div>
            <div class="object">
                <img src="../assets/buy-comics-shop-locator.png" alt="">
                <span>COMIC SHOP LOCATOR</span>
            </div>
            <div class="object">
                <img class="svg" src="../assets/buy-dc-power-visa.svg" alt="">
                <span class="svg_text">DC POWER VISA</span>
            </div>
        </div>
    </section>
    <section class="third">
<div class="sx">
    <ul>
        <li class="LIF">DC COMICS</li>
        <li>Characters</li>
        <li>Comics</li>
        <li>Movies</li>
        <li>TV</li>
        <li>Games</li>
        <li>Videos</li>
        <li>News</li>
    </ul>
        <ul>
        <li class="LIF">DC</li>
        <li>Terms Of Use</li>
        <li>Privacy policy(New)</li>
        <li>Ad Choices</li>
        <li>Advertising</li>
        <li>Jobs</li>
        <li>Subscriptions</li>
        <li>Talent Workshops</li>
        <li>CPSC Certificates</li>
        <li>Ratings</li>
        <li>Shop Help</li>
        <li>Contact Us</li>
    </ul>
    <ul>
        <li class="LIF">SITES</li>
        <li>DC</li>
        <li>MAD Magazine</li>
        <li>MDC Kids</li>
        <li>DC Universe</li>
        <li>DC Power Visa</li>
    </ul>
        <ul>
        <li class="LIF">SHOP</li>
        <li>Shop DC</li>
        <li>Shop DC Collectibles</li>
        </ul>
</div>
<div class="dx"></div>
    </section>
</div>
</template>
<script>
export default {
}
</script>

<style lang="scss">
.first{
    background-color: black;
    color :white;
    margin: auto;
    padding:2.5rem;
    div{
        font-size: 20px;
        font-weight: bold;
        margin-left: 16.5rem;
    }
}
.second{
    background-color: lightseagreen;
    .container{
        padding: 2.5rem;
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
.object{
    padding: 2.5rem;
}
        img{
            height: 50px;
        }
        span{
            color: white;
            margin-left: 1rem;
            vertical-align:20px;
        }
    }
}
.svg{
    height: 40px !important;
}
.svg_text{
    vertical-align:15px !important;
}
.third{
    background-image: url('../assets/footer-bg.jpg');
    background-repeat: no-repeat;
    background-size:cover;
    height: 400px;
    display: flex;
    flex-direction: row;
    justify-content: space-around;
}
.sx{
    display: flex;
    flex-direction: row;
    ul{
        color:#8f8f90;
        display: flex;
        flex-direction: column;
        margin: 1rem;
        height: max-content;
        .LIF{
            color: white;
            font-size: 20px;
            padding: 5px 0;
        }
    }
}
.dx{
     background-image:url('../assets/dc-logo-bg.png');
     background-position: right;
     width: 562px;
     background-repeat: no-repeat;
}
</style>;