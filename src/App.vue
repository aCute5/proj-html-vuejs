<template>
  <div id="app">
    <HeaderPage></HeaderPage>
  </div>
</template>

<script>
import HeaderPage from "@/components/HeaderPage.vue";

export default {
  name: "App",
  components: {
    HeaderPage,
  },
};
</script>

<style lang="scss">
@import "~bootstrap/scss/bootstrap";
@import url("https://fonts.googleapis.com/css2?family=Lora:wght@500&display=swap");
#app {
  font-family: "Lora", serif;
}
</style>
