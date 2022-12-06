<template>
  <div class="footer">
    <div class="container socials">
      <div class="row gy-5 text-center">
        <div class="col-12">
          <img src="@/img/logo-restaurant.png" alt="" />
        </div>
        <div class="offset-4 col-4 text-center">
          <p class="text-white">
            Quam eu sit mass condimentum.Volupatat non pulvinar aliquet nunc.
            Quam eu proin sit massa condimentum.
          </p>
        </div>
        <div class="col-12 brands">
          <font-awesome-icon
            class="brand-icons"
            icon="fa-brands fa-facebook-f"
          />
          <font-awesome-icon class="brand-icons" icon="fa-brands fa-twitter" />
          <font-awesome-icon class="brand-icons" icon="fa-brands fa-youtube" />
          <font-awesome-icon
            class="brand-icons"
            icon="fa-brands fa-instagram"
          />
          <font-awesome-icon
            class="brand-icons"
            icon="fa-brands fa-linkedin-in"
          />
        </div>

        <div class="col-12 copyright info-promotions">
          <span>
            Copyright 2012-2019 &#x7c; All Rights Deserved &#x7c; Powered by
            WordPress &#x7c; ThemeFusion
          </span>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "FooterPage",
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

.footer {
  height: 100vh;
  background-color: black;
  background-image: url("@/img/footer2x.jpg");
  background-size: contain;
  background-repeat: no-repeat;
}
.socials {
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
  color: white;
}
.brands {
  display: flex;
  justify-content: center;
  font-size: 1.2rem;
  color: black;
}
.brands .brand-icons {
  background-color: white;
  clip-path: circle(40%);
  padding: 2rem;
}
.footer .copyright {
  margin-top: 300px;
}
.info-promotions {
  font-size: 0.8rem;
  color: $tundora;
  font-variant: small-caps;
}
</style>
