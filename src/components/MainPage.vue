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
  </div>
</template>

<script>
export default {
  name: "MainPage",
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
.main {
  height: 100vh;
  background-color: white;
}
.white-section {
  height: 50vh;
  padding: 5rem;
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
  background-color: rgb(0, 0, 0);
  width: 50px;
  height: 1.2px;
  opacity: 0.3;
  margin: auto;
}
</style>
