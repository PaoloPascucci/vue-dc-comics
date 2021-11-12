<template>
  <div>
    <section class="first">
      <div class="jumbotron">
        <div class="series">current series</div>
      </div>
      <div class="container3">
        <!-- v-for:="game in games" -->
        <game
          v-for="game in games"
          :key="game.id"
          :image="game.thumb"
          :title="game.series"
        />
        <div class="button">
          <button class="btnL" type="submit">Load More</button>
        </div>
      </div>
    </section>
    <section class="second">
      <div class="container">
        <div class="object">
          <img src="../assets/buy-comics-digital-comics.png" alt="" />
          <span>DIGITAL COMICS</span>
        </div>
        <div class="object">
          <img src="../assets/buy-comics-merchandise.png" alt="" />
          <span>DC MERCHANDISE</span>
        </div>
        <div class="object">
          <img src="../assets/buy-comics-subscriptions.png" alt="" />
          <span>SUBSCRIPTION</span>
        </div>
        <div class="object">
          <img src="../assets/buy-comics-shop-locator.png" alt="" />
          <span>COMIC SHOP LOCATOR</span>
        </div>
        <div class="object">
          <img class="svg" src="../assets/buy-dc-power-visa.svg" alt="" />
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
          <li class="LIF">SHOP</li>
          <li>Shop DC</li>
          <li>Shop DC Collectibles</li>
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
      </div>
      <div class="dx"></div>
    </section>
  </div>
</template>
<script>
import game from "./game.vue";
export default {
  components: {
    game,
  },
  data() {
    return {
      games: [
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
          price: "$19.99",
          series: "Action Comics",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
          price: "$3.99",
          series: "American Vampire 1976",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
          price: "$16.99",
          series: "Aquaman",
          type: "graphic novel",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
          price: "$2.99",
          series: "Batgirl",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$3.99",
          series: "Batman",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$2.99",
          series: "Batman Beyond",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
          price: "$3.99",
          series: "Batman/Superman",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
          price: "$4.99",
          series: "Batman/Superman Annual",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
          price: "$5.99",
          series: "Batman: The Joker War Zone",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
          price: "$6.99",
          series: "Batman: Three Jokers",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
          price: "$4.99",
          series: "Batman: White Knight Presents: Harley Quinn",
          type: "comic book",
        },
        {
          thumb:
            "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
          price: "$16.99",
          series: "Catwoman",
          type: "graphic novel",
        },
      ],
    };
  },
};
</script>

<style lang="scss">
.first {
  background-color: black;
  color: white;
}
.second {
  background-color: #0282f9;
  .container {
    padding: 2.5rem;
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    .object {
      padding: 2.5rem;
    }
    img {
      height: 50px;
    }
    span {
      color: white;
      margin-left: 1rem;
      vertical-align: 20px;
    }
  }
}
.svg {
  height: 40px !important;
}
.svg_text {
  vertical-align: 15px !important;
}
.third {
  background-image: url("../assets/footer-bg.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  height: 400px;
  display: flex;
  flex-direction: row;
  justify-content: space-around;
}
.sx {
  display: flex;
  flex-direction: row;
  ul {
    list-style: none;
    color: #8f8f90;
    display: flex;
    flex-direction: column;
    margin: 1rem;
    height: max-content;
    .LIF {
      color: white;
      font-size: 20px;
      padding: 5px 0;
    }
    li {
      line-height: 25px;
    }
  }
}
.dx {
  background-image: url("../assets/dc-logo-bg.png");
  background-position: right;
  width: 562px;
  background-repeat: no-repeat;
}
.jumbotron {
  background-image: url("../assets/jumbotron.jpg");
  background-repeat: no-repeat;
  background-size: cover;
  height: 400px;
  position: relative;
  .series {
    background-color: #0282f9;
    color: white;
    text-transform: uppercase;
    font-weight: bold;
    width: 10.5%;
    padding: 1rem;
    position: absolute;
    bottom: -25px;
    left: 90px;
    text-align: center;
  }
}
.container3 {
  display: flex;
  flex-wrap: wrap;
  padding: 2.5rem;
  .card {
    width: calc(100% / 6);
    text-align: center;
    padding: 0.25rem;
    img {
      height: 170px;
      width: 150px;
      object-fit: cover;
      object-position: top left;
    }
  }
  .button {
    width: 100%;
    display: flex;
    justify-content: center;
    align-self: center;
    margin-top: 4rem;
  }
  .btnL {
    color: white;
    background-color: #0282f9;
    padding: 0.5rem;
    width: 180px;
    border: none;
    text-transform: uppercase;
    font-weight: bold;
  }
}
</style>;