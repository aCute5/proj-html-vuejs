<template>
  <div id="app">
    <HeaderPage></HeaderPage>
    <MainPage></MainPage>
  </div>
</template>

<script>
import HeaderPage from "@/components/HeaderPage.vue";
import MainPage from "./components/MainPage.vue";

export default {
  name: "App",
  components: {
    HeaderPage,
    MainPage,
  },
};
</script>

<style lang="scss">
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

@import "~bootstrap/scss/bootstrap";
@import url("https://fonts.googleapis.com/css2?family=Lora:wght@500&display=swap");
@import url("https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap");

* {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
a {
  text-decoration: none;
}
#app {
  font-family: "Lora", serif;
}
</style>
