<template>
  <div class="main">
    <div class="container white-section">
      <div class="row">
        <div class="col-6">
          <div class="row">
            <div class="col-12 p-signature">
              <p>
                <strong class="caps">HAC TELLUS, FELIS RISUS AT</strong>
                matis matis.Eget euismod semper eget tortor, donec amet,
                blandit. Tristique facilisi fauctibus elementum feugiat in nam
                in feugiat. Ipsum odio etiam duis facilis amet vuluputate.
              </p>
            </div>
            <div class="col-12">
              <h1>FOOD IS OUR COMMON GROUND, A UNIVERSAL EXPERIENCE</h1>
            </div>
            <div class="col-12 p-signature">
              <p>
                Tristique tempus condimentum diam donec.Condimentum ullamcorper
                sit elemenutm hendererit mi nulla in conequat, ut. Metus,nullam
                scelerisque netus viverra dui.
              </p>
            </div>
            <div class="col-12">
              <img src="@/img/signature-200x172.jpg" alt="" />
            </div>
          </div>
        </div>
        <div class="col-6 california">
          <img class="california-roll" src="@/img/info22x.jpg" alt="" />
          <div class="info-img">california rolls - $22</div>
        </div>
      </div>
      <div class="row container-sushi mt-5 pt-5">
        <div class="col-4">
          <div class="row sushi-cards gy-3">
            <div class="col-12">
              <img src="@/img/sushi-1.png" alt="" />
            </div>

            <div class="col-12">
              <h3>THE BEST TABLE IN TOWN</h3>
            </div>
            <div class="col-12">
              <div class="linewhite"></div>
            </div>
            <div class="col-12">
              <p>
                Sed aeneam egestas ut aliquam turpis mauris molestie. Vitae
                tellus tempor sem id tempus neque, tellus turpis turpis. Morbi
                tortor id gravida aliquet.
              </p>
            </div>
            <div class="col-12">
              <button type="button" class="btn">EXPLORE THE MENU</button>
            </div>
          </div>
        </div>
        <div class="col-4">
          <div class="row sushi-cards gy-3">
            <div class="col-12">
              <img src="@/img/sushi-2.png" alt="" />
            </div>

            <div class="col-12">
              <h3>PERFECT FOR GROUPS</h3>
            </div>
            <div class="col-12">
              <div class="linewhite"></div>
            </div>
            <div class="col-12">
              <p>
                Sed aeneam egestas ut aliquam turpis mauris molestie. Vitae
                tellus tempor sem id tempus neque, tellus turpis turpis. Morbi
                tortor id gravida aliquet.
              </p>
            </div>
            <div class="col-12">
              <button type="button" class="btn">MAKE A RESERVATION</button>
            </div>
          </div>
        </div>
        <div class="col-4">
          <div class="row sushi-cards gy-3">
            <div class="col-12">
              <img src="@/img/sushi-3.png" alt="" />
            </div>

            <div class="col-12">
              <h3>FRESH PRODUCE EVERYDAY</h3>
            </div>
            <div class="col-12">
              <div class="linewhite"></div>
            </div>
            <div class="col-12">
              <p>
                Sed aeneam egestas ut aliquam turpis mauris molestie. Vitae
                tellus tempor sem id tempus neque, tellus turpis turpis. Morbi
                tortor id gravida aliquet.
              </p>
            </div>
            <div class="col-12">
              <button type="button" class="btn">LEARN MORE ABOUT US</button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <SliderPage
      v-for="objSlider in arrSlider.slice(0, 1)"
      :key="objSlider"
      :info="objSlider"
      :style="backgroundStyles(objSlider.background)"
    ></SliderPage>
    <div class="critic container py-5">
      <h2 class="text-center critic-title">What critics are saying about us</h2>
      <div class="linegrey"></div>

      <div class="row gy-3 py-5">
        <div class="col-12">
          <div class="row gx-0">
            <div class="col-6">
              <img src="@/img/blog72x-600x687.jpg" class="criticimg" alt="" />
            </div>
            <div class="col-6 card-critic black">
              <div class="row gy-4">
                <div class="offset-2 col-12">
                  <div class="overtitle">
                    <span> MEGGY STEWART</span>
                  </div>
                </div>
                <div class="offset-2 col-12">
                  <h2>NEW YORK TIMES</h2>
                </div>
                <div class="offset-2 col-12">
                  <font-awesome-icon class="stars" icon="fa-solid fa-star" />
                  <font-awesome-icon class="stars" icon="fa-solid fa-star" />
                  <font-awesome-icon class="stars" icon="fa-solid fa-star" />
                  <font-awesome-icon class="stars" icon="fa-solid fa-star" />
                  <font-awesome-icon class="stars" icon="fa-solid fa-star" />
                </div>
                <div class="offset-2 col-12">
                  <div class="linewhite"></div>
                </div>
                <div class="offset-2 col-9">
                  <p>
                    Non arcu mauris tortor ultrices mollis tellus eursmod
                    fermentum.Habitant amet tincidunt id sapein accusan sed at.
                  </p>
                </div>
                <div class="offset-2 col-9">
                  <p>
                    Mmalesuada ullamcorper amet-Pretium pretium idgnissim nisi.
                  </p>
                </div>
                <div class="offset-2 col-9">
                  <button type="button" class="btn">READ FULL ARTICLE</button>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-12 d-flex layoutfor2cards">
          <div class="col-5 card-critic p-5 first">
            <div class="row p-5 gy-4">
              <div class="offset-2 col-12">
                <div class="overtitle">
                  <span> MAREY MAXEY</span>
                </div>
              </div>
              <div class="offset-2 col-12">
                <h2>THE GUARDIAN</h2>
              </div>
              <div class="offset-2 col-12">
                <font-awesome-icon class="stars" icon="fa-solid fa-star" />
                <font-awesome-icon class="stars" icon="fa-solid fa-star" />
                <font-awesome-icon class="stars" icon="fa-solid fa-star" />
                <font-awesome-icon class="stars" icon="fa-solid fa-star" />
                <font-awesome-icon class="stars" icon="fa-solid fa-star" />
              </div>
              <div class="offset-2 col-12">
                <div class="linewhite"></div>
              </div>
              <div class="offset-2 col-9">
                <p>
                  Non arcu mauris tortor ultrices mollis tellus eursmod
                  fermentum.Habitant amet tincidunt id sapein accusan sed.
                </p>
              </div>
              <div class="offset-2 col-9">
                <button type="button" class="btn">READ FULL ARTICLE</button>
              </div>
            </div>
          </div>
          <div class="col-5 card-critic p-5 second">
            <div class="row p-5 gy-4">
              <div class="offset-2 col-12">
                <div class="overtitle">
                  <span> MAREY MAXEY</span>
                </div>
              </div>
              <div class="offset-2 col-12">
                <h2>THE GUARDIAN</h2>
              </div>
              <div class="offset-2 col-12">
                <font-awesome-icon class="stars" icon="fa-solid fa-star" />
                <font-awesome-icon class="stars" icon="fa-solid fa-star" />
                <font-awesome-icon class="stars" icon="fa-solid fa-star" />
                <font-awesome-icon class="stars" icon="fa-solid fa-star" />
                <font-awesome-icon class="stars" icon="fa-solid fa-star" />
              </div>
              <div class="offset-2 col-12">
                <div class="linewhite"></div>
              </div>
              <div class="offset-2 col-9">
                <p>
                  Non arcu mauris tortor ultrices mollis tellus eursmod
                  fermentum.Habitant amet tincidunt id sapein accusan sed.
                </p>
              </div>
              <div class="offset-2 col-9">
                <button type="button" class="btn">READ FULL ARTICLE</button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="container-fluid pao">
      <div class="info-pao">KUNG PAO CHICKEN - $32</div>
    </div>
    <div class="container promotions">
      <h2 class="text-center py-5 critic-title">Latest news & promotions</h2>
      <div class="linegrey"></div>
      <div class="row container">
        <div class="col-4">
          <div class="row gy-3">
            <div class="col-12">
              <img
                src="@/img/blog92x-600x687.jpg"
                class="img-promotion"
                alt=""
              />
            </div>
            <div class="col-12 text-center">
              <h3>The best coffe in town</h3>
            </div>
            <div class="col-12 text-center info-promotions">
              <span>
                BY Admin &#x7c; January 7th, 2020 &#x7c; Categories:News
              </span>
            </div>
          </div>
        </div>
        <div class="col-4">
          <div class="row gy-3">
            <div class="col-12">
              <img
                src="@/img/blog72x-600x687.jpg"
                class="img-promotion"
                alt=""
              />
            </div>
            <div class="col-12 text-center">
              <h3>The best coffe in town</h3>
            </div>
            <div class="col-12 text-center info-promotions">
              <span>
                BY Admin &#x7c; January 7th, 2020 &#x7c; Categories:News
              </span>
            </div>
          </div>
        </div>
        <div class="col-4">
          <div class="row gy-3">
            <div class="col-12">
              <img
                src="@/img/blog82x-600x687.jpg"
                class="img-promotion"
                alt=""
              />
            </div>
            <div class="col-12 text-center">
              <h3>The best coffe in town</h3>
            </div>
            <div class="col-12 text-center info-promotions">
              <span>
                BY Admin &#x7c; January 7th, 2020 &#x7c; Categories:News
              </span>
            </div>
          </div>
        </div>
      </div>
    </div>
    <SliderPage
      v-for="objSlider in arrSlider.slice(1)"
      :key="objSlider"
      :info="objSlider"
      :style="backgroundStyles(objSlider.background)"
      class="mt-5"
    ></SliderPage>
    <div class="container mt-5">
      <div class="row">
        <div class="mt-5 col-4 menu-grey">
          <div class="col-12"><h1>HORS D'OEUVRES</h1></div>
          <div class="row mt-5">
            <div class="col-12">
              <div class="row">
                <h3 class="product col-6">AHI SALMON NIGIRI</h3>
                <span class="price offset-4 col-2">$48</span>
                <p class="col-12">
                  Eget voluptate vitae quis rutrum blandit sed. Quam nulla sit
                  lacinia
                </p>
              </div>
            </div>
            <div class="col-12">
              <div class="row">
                <h3 class="product col-6">AHI SALMON NIGIRI</h3>
                <span class="price offset-4 col-2"> $48</span>
                <p class="col-12">
                  Eget voluptate vitae quis rutrum blandit sed. Quam nulla sit
                  lacinia
                </p>
              </div>
            </div>
            <div class="col-12">
              <div class="row">
                <h3 class="product col-6">AHI SALMON NIGIRI</h3>
                <span class="price offset-4 col-2"> $48</span>
                <p class="col-12">
                  Eget voluptate vitae quis rutrum blandit sed. Quam nulla sit
                  lacinia
                </p>
              </div>
            </div>
            <div class="col-12">
              <div class="row">
                <h3 class="product col-6">AHI SALMON NIGIRI</h3>
                <span class="price offset-4 col-2"> $48</span>
                <p class="col-12">
                  Eget voluptate vitae quis rutrum blandit sed. Quam nulla sit
                  lacinia
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="mb-5 col-4 menu-black">
          <div class="col-12"><h1>HORS D'OEUVRES</h1></div>
          <div class="row mt-5">
            <div class="col-12">
              <div class="row">
                <h3 class="product col-6">AHI SALMON NIGIRI</h3>
                <span class="price offset-4 col-2">$48</span>
                <p class="col-12">
                  Eget voluptate vitae quis rutrum blandit sed. Quam nulla sit
                  lacinia
                </p>
              </div>
            </div>
            <div class="col-12">
              <div class="row">
                <h3 class="product col-6">AHI SALMON NIGIRI</h3>
                <span class="price offset-4 col-2"> $48</span>
                <p class="col-12">
                  Eget voluptate vitae quis rutrum blandit sed. Quam nulla sit
                  lacinia
                </p>
              </div>
            </div>
            <div class="col-12">
              <div class="row">
                <h3 class="product col-6">AHI SALMON NIGIRI</h3>
                <span class="price offset-4 col-2"> $48</span>
                <p class="col-12">
                  Eget voluptate vitae quis rutrum blandit sed. Quam nulla sit
                  lacinia
                </p>
              </div>
            </div>
            <div class="col-12">
              <div class="row">
                <h3 class="product col-6">AHI SALMON NIGIRI</h3>
                <span class="price offset-4 col-2"> $48</span>
                <p class="col-12">
                  Eget voluptate vitae quis rutrum blandit sed. Quam nulla sit
                  lacinia
                </p>
              </div>
            </div>
          </div>
        </div>
        <div class="mt-5 col-4 menu-grey">
          <div class="col-12"><h1>HORS D'OEUVRES</h1></div>
          <div class="row mt-5">
            <div class="col-12">
              <div class="row">
                <h3 class="product col-6">AHI SALMON NIGIRI</h3>
                <span class="price offset-4 col-2">$48</span>
                <p class="col-12">
                  Eget voluptate vitae quis rutrum blandit sed. Quam nulla sit
                  lacinia
                </p>
              </div>
            </div>
            <div class="col-12">
              <div class="row">
                <h3 class="product col-6">AHI SALMON NIGIRI</h3>
                <span class="price offset-4 col-2"> $48</span>
                <p class="col-12">
                  Eget voluptate vitae quis rutrum blandit sed. Quam nulla sit
                  lacinia
                </p>
              </div>
            </div>
            <div class="col-12">
              <div class="row">
                <h3 class="product col-6">AHI SALMON NIGIRI</h3>
                <span class="price offset-4 col-2"> $48</span>
                <p class="col-12">
                  Eget voluptate vitae quis rutrum blandit sed. Quam nulla sit
                  lacinia
                </p>
              </div>
            </div>
            <div class="col-12">
              <div class="row">
                <h3 class="product col-6">AHI SALMON NIGIRI</h3>
                <span class="price offset-4 col-2"> $48</span>
                <p class="col-12">
                  Eget voluptate vitae quis rutrum blandit sed. Quam nulla sit
                  lacinia
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="mt-5 container-fluid braised">
      <div class="container-product">
        <div class="offset-2 col-4 p-5">
          <div class="row p-5 black-product">
            <div class="col-6">
              <h1>Braised Abalone</h1>
            </div>
            <div class="col-2 offset-2">
              <span class="price"> $52</span>
            </div>
            <div class="col-12">
              <div class="linewhite"></div>
            </div>
            <div class="col-12">
              <p>
                Pretium accusmsan portitor viverra leo gravida mollis
                imperdiet.Fringilla nibh pharetra sociis leo amet.
              </p>
            </div>
            <div class="col-12">
              <button class="btn">view in the menu</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import SliderPage from "@/components/SliderPage.vue";

export default {
  name: "MainPage",
  components: {
    SliderPage,
  },
  data() {
    return {
      arrSlider: [
        {
          background: "/img/slider32x.jpg",
          overtitle: "Fine dining Experience",
          title: "The best Table in Town",
          paragraph:
            "Pellentesque vitae viverra risus, sagittis. Venenatis ridiculus scelerisque nisi in urna nulla.",
          button: "Explore the menu",
        },
        {
          background: "/img/slider72x-scaled.jpg",
          overtitle: "Enjoy your meal at home",
          title: "Take out now available",
          paragraph:
            "Pellentesque vitae viverra risus, sagittis. Venenatis ridiculus scelerisque nisi in urna nulla.",
          button:
            "View Take out menu" + <font-awesome-icon icon="fa-solid fa-car" />,
        },
      ],
    };
  },
  methods: {
    backgroundStyles(image) {
      return {
        "background-image": `url(${image})`,
      };
    },
  },
};
</script>

<style lang="scss" scoped>
$black: #030303;
$tundora: #434243;
$silver: #bcbcbc;
$almond: #937a6b;
$oregon: #944402;
$easternblue: #2787b2;
$christine: #f3790c;
$equator: #e3bd5e;
$christi: #69a10e;
$zeus: #1f1914;
$sisal: #d6cbbd;
$mantle: #88978d;
$fieryorange: #b44a13;
$slategrey: #6f7f8c;

.btn:hover {
  transform: scale(1.2);
  color: black;
  background-color: white;
}
.white-section {
  padding: 5rem;
}
.white-section img:hover {
  transform: scale(1.1);
}
.white-section img:hover + .info-img {
  transform: scale(1.2);
}
.p-signature {
  line-height: 2.3rem;
}
.caps {
  font-variant: small-caps;
}
.california {
  position: relative;
}
.california-roll {
  width: 100%;
  position: relative;
}
.info-img {
  font-variant: small-caps;
  position: absolute;
  left: 40%;
  bottom: 1%;
  font-weight: bold;
  color: black;
}
.sushi-cards {
  line-height: 2rem;
  text-align: center;
}
.btn {
  padding: 1rem;
  color: rgb(0, 0, 0);
  border: 0.2px solid $silver;
  border-radius: 0px;
  font-variant: small-caps;
  font-size: 0.8rem;
  letter-spacing: 0.1rem;
}
.linewhite {
  background-color: #ffffff;
  width: 50px;
  height: 1.2px;
}
.linegrey {
  background-color: silver;
  margin: 1rem auto;
  width: 100px;
  height: 1.2px;
}
.critic .container {
  max-width: 800px;
}
.critic-title {
  font-family: "Lora", serif;
  font-size: 3rem;
}
//Style per il componente card da cancellare e mettere nel CriticsCard

.card-critic {
  padding: 1rem;
  display: flex;
  color: white;
  align-items: center;
  line-height: 1.5rem;
}
.card-critic.black:hover {
  transform: translate(-10px, -5%) scale(1.1);
  transition: all 0.5s ease-in;
}
.layoutfor2cards {
  justify-content: space-between;
}
.layoutfor2cards .col-5 {
  flex-basis: 49%;
}
.card-critic.first {
  background-image: url("@/img/info52x.jpg");
  box-shadow: inset 0px 250px 250px 0px rgba($color: #000000, $alpha: 1);
  background-position: 50% 40%;
  background-size: cover;
  background-repeat: no-repeat;
}
.card-critic.second {
  background-image: url("@/img/info12x.jpg");
  box-shadow: inset 0px 250px 250px 0px rgba($color: #000000, $alpha: 1);
  background-position: 50% 40%;
  background-size: cover;
  background-repeat: no-repeat;
}
.card-critic.first:hover,
.card-critic.second:hover {
  box-shadow: none;
  transform: scale(1.1);
  transition: all 0.5s ease-in;
}
.card-critic h2 {
  font-size: 4rem;
}
.black {
  background-color: #030303;
}
.card-critic p {
  line-height: 1.5rem;
  font-size: 1.1rem;
}
.criticimg {
  width: 100%;
  height: 100%;
}
.overtitle {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 3rem;
}
.overtitle span {
  font-variant: small-caps;
  font-size: 0.8rem;
  letter-spacing: 0.1rem;
  color: #bcbcbc;
}
.stars {
  font-size: 1rem;
}
.btn {
  color: white;
  border: 0.2px solid white;
  border-radius: 0px;
  font-variant: small-caps;
  font-size: 0.8rem;
  letter-spacing: 0.1rem;
}
.pao {
  position: relative;
  background-image: url("@/img/page52x.jpg");
  height: 100vh;
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
}
.info-pao {
  font-variant: small-caps;
  position: absolute;
  left: 45%;
  bottom: 22%;
  font-size: 0.8rem;
  font-weight: bold;
  letter-spacing: 0.2rem;
  color: rgb(255, 255, 255);
}
.info-promotions {
  color: $tundora;
  font-variant: small-caps;
}
.img-promotion {
  min-height: 560px;
  width: 100%;
}
// MENU STYLE
.container .menu-grey {
  padding: 2rem;
  background-color: #e8e8e8;
  line-height: 2rem;
}
.container .menu-black {
  padding: 2rem;
  background-color: black;
  color: white;
  line-height: 2rem;
}
.price {
  font-variant: small-caps;
  letter-spacing: 0.1rem;
  font-weight: bold;
}
.braised {
  position: relative;
  background-image: url("@/img/hero42x.jpg");
  height: 100vh;
  background-position: center;
  background-size: cover;
  background-repeat: no-repeat;
}
// STAND ALONE PRODUCT
.container-product {
  align-items: center;
  display: flex;
}
.black-product {
  background-color: black;
  color: white;
  gap: 2rem;
  line-height: 2.3rem;
}
.black-product .price {
  vertical-align: sub;
}
</style>
