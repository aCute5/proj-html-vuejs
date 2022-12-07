<template>
  <div class="slider container-fluid">
    <div class="row">
      <div class="col-4 offset-8 slide-title">
        <div class="row">
          <div class="overtitle col-12 gy-5">
            <div class="linewhite"></div>
            <span>{{ info.overtitle }}</span>
          </div>
          <div class="col-12 gy-5">
            <h1 class="title">{{ info.title }}</h1>
          </div>
          <p class="col-12 gy-5">
            {{ info.paragraph }}
          </p>
          <div class="col-12 gy-5">
            <button type="button" class="btn">{{ info.button }}</button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "SliderPage",
  props: {
    info: Object,
  },
};
</script>

<style lang="scss" scoped>
.slider {
  height: 100vh;
  background-repeat: no-repeat;
  background-size: contain;
  background-position-x: 0%;
  background-color: black;
  color: white;
}
.slide-title {
  height: 100%;
  padding: 5rem;
}
.slide-title p {
  font-size: 1.2;
  line-height: 1.8rem;
}
.overtitle {
  gap: 1rem;
  display: flex;
  align-items: center;
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
