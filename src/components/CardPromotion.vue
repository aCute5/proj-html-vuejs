<template>
  <div class="col-4">
    <div class="row gy-3 relative-promotions">
      <div class="col-12">
        <img :src="card.image" class="img-promotion" alt="" />
        <div class="col-12 text-center hover-promotions">
          <font-awesome-icon icon="fa-solid fa-link" />
          <h3>The best coffe in town</h3>
          <span>News</span>
        </div>
      </div>
      <div class="col-12 text-center">
        <h3>{{ card.title }}</h3>
      </div>
      <div class="col-12 text-center info-promotions">
        <span> BY Admin &#x7c; January 7th, 2020 &#x7c; Categories:News </span>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "CardPromotion",
  props: {
    card: Object,
  },
};
</script>

<style lang="scss" scoped>
$tundora: #434243;
.container {
  display: flex;
  flex-wrap: nowrap;
}
.info-promotions {
  color: $tundora;
  font-variant: small-caps;
}
.img-promotion {
  min-height: 560px;
  width: 100%;
}
.relative-promotions {
  position: relative;
}
.hover-promotions {
  position: absolute;
  bottom: 50%;
  right: 1%;
  opacity: 0;
  color: white;
}
.img-promotion:hover + .hover-promotions {
  transform: translate(0px, 20%);
  bottom: 30%;
  opacity: 1;
  transform: scale(1.2);
  transition: all 0.5s ease-in;
}
.img-promotion:hover {
  transform: translate(0px, 20%);
  transition: all 0.5s ease-in;
}
</style>
