<template>
  <div class="container-fluid header">
    <nav class="navbar row">
      <div class="col-4">
        <a class="navbar-brand" href="#">
          <img src="@/img/logo-restaurant-2x-400x77.png" alt="" />
        </a>
      </div>
      <ul class="nav col-6">
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Culinary History</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Our Team</a>
        </li>
        <li class="nav-item">
          <a class="nav-link active" aria-current="page" href="#">Our Menu</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Takeout</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Link</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#"
            ><font-awesome-icon icon="fa-solid fa-cart-shopping"
          /></a>
        </li>
      </ul>
    </nav>
    <div class="row slider">
      <div class="fixed-buttons">
        <button class="btn btn-light"><span>demos</span></button>
        <button class="btn btn-light">
          <sup>$</sup> <span class="price">39</span>
          <span class="sale"> sale</span>
        </button>
      </div>
      <div class="col-4 slide-title">
        <div class="row">
          <div class="overtitle col-8 offset-1">
            <div class="linewhite"></div>
            <span> the best table in town</span>
          </div>
          <div class="col-12 offset-4 gy-5">
            <h1 class="title">FINE DINING</h1>
            <h1 class="title">EXPERIENCE</h1>
            <p class="col-12 gy-5">
              Pellenstque vitae viverra risus,sagittis.Venenatis ridicuos
              sceleritsque nis in unrna nulla. Sit tempora et nisl,ac felis.
            </p>
            <div class="col-12 gy-5">
              <button type="button" class="btn">EXPLORE THE MENU</button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "HeaderPage",
};
</script>
<style scoped lang="scss">
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
.header {
  height: 70vh;
  background-image: url("@/img/slider52x.jpg");
  background-repeat: no-repeat;
  background-size: contain;
  background-position-x: 100%;
  background-color: black;
  color: white;
  position: relative;
}
.navbar {
  display: flex;
  justify-content: space-between;
}
.nav {
  display: flex;
  justify-content: space-around;
  font-size: smaller;
  align-items: center;
}
.navbar-brand img {
  width: 60%;
  padding: 0.5rem;
}
.nav-item a {
  opacity: 0.8;
}
.nav-item a:hover {
  opacity: 1;
  color: white;
}
.nav-item a:focus {
  color: white;
}
.nav .nav-item,
a {
  color: white;
}
.fixed-buttons {
  position: fixed;
  top: 15%;
  left: 96.5%;
  display: flex;
  flex-direction: column;
  gap: 0.5rem;
}
.fixed-buttons .btn {
  width: 3.5rem;
  height: 3.5rem;
  border-radius: 0.3rem;
  color: $christi;
  line-height: 1rem;
  font-size: 1rem;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  padding-top: 1rem;
}
.btn sup {
  align-self: flex-start;
  font-size: 0.8rem;
  font-weight: bold;
}
.price {
  font-size: 1.3rem;
  font-weight: bold;
}
.sale {
  font-size: 1rem;
  line-height: 0.8rem;
  color: #434243;
}
.slide-title {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100%;
  padding: 5rem;
}
.slide-title p {
  font-size: 1.2;
  line-height: 1.8rem;
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
}
.linewhite {
  background-color: white;
  width: 40px;
  height: 1.2px;
  opacity: 0.5;
}
.title {
  font-size: 5rem;
  font-family: "Bebas Neue", cursive;
}
.btn {
  color: white;
  border: 0.2px solid white;
  border-radius: 0px;
  font-variant: small-caps;
  font-size: 0.8rem;
  letter-spacing: 0.1rem;
}
</style>
