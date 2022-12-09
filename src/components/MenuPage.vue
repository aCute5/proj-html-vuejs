<template>
  <div class="container mt-5">
    <div class="row">
      <div class="mt-5 col-4 menu-grey">
        <div class="col-12"><h1>HORS D'OEUVRES</h1></div>
        <div class="row mt-5">
          <div class="col-12" v-for="menu in arrMenuWhite" :key="menu">
            <div class="row">
              <h3 class="product col-6">{{ menu.name }}</h3>
              <span class="price offset-4 col-2">{{ menu.price }}</span>
              <p class="col-12">
                {{ menu.paragraph }}
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="mb-5 col-4 menu-black">
        <div class="col-12"><h1>MAIN COURSE</h1></div>
        <div class="row mt-5">
          <div class="col-12" v-for="menu in arrMain" :key="menu">
            <div class="row">
              <h3 class="product col-6">{{ menu.name }}</h3>
              <span class="price offset-4 col-2">{{ menu.price }}</span>
              <p class="col-12">
                {{ menu.paragraph }}
              </p>
            </div>
          </div>
        </div>
      </div>
      <div class="mt-5 col-4 menu-grey">
        <div class="col-12"><h1>DESSERTS</h1></div>
        <div class="row mt-5">
          <div class="col-12" v-for="menu in arrDesserts" :key="menu">
            <div class="row">
              <h3 class="product col-6">{{ menu.name }}</h3>
              <span class="price offset-4 col-2"> {{ menu.price }}</span>
              <p class="col-12">
                {{ menu.paragraph }}
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MenuPage",
  data() {
    return {
      arrMenuWhite: [
        {
          name: "AHI SALMON NIGIRI",
          paragraph:
            "Eget voluptate vitae quis rutrum blandit sed. Quam nulla sit lacinia",
          price: "$48",
        },
        {
          name: "UMI MASU SALAD",
          paragraph:
            "Eget voluptate vitae quis rutrum blandit sed. Quam nulla sit lacinia",
          price: "$21",
        },
        {
          name: "TEMAKI WITH CRAB",
          paragraph:
            "Eget voluptate vitae quis rutrum blandit sed. Quam nulla sit lacinia",
          price: "$32",
        },
        {
          name: "CALIFORNIA ROLLS",
          paragraph:
            "Eget voluptate vitae quis rutrum blandit sed. Quam nulla sit lacinia",
          price: "$22",
        },
      ],
      arrDesserts: [
        {
          name: "Chocolate ball cake",
          paragraph:
            "In pellentesque in felis massa vehicula.In sed sed euismod ut.",
          price: "$13",
        },
        {
          name: "Lime Pie with Crust",
          paragraph:
            "Mollis ornare sit sapien, sodales. Cursus duis proin semper quisque.",
          price: "$14",
        },
        {
          name: "RASPBERRY PEAR CAKE",
          paragraph:
            "Eget vulputate vitae quis rutrum blandit sed.Quam nulla sit",
          price: "$18",
        },
        {
          name: "cafè AU LAIT",
          paragraph:
            "Eget vulputate vitae quis rutrum blandit sed.Quam nulla sit",
          price: "$6",
        },
      ],
      arrMain: [
        {
          name: "Braised Abalone",
          paragraph:
            "Eget vulputate vitae quis rutrum blandit sed.Quam nulla sit",
          price: "$52",
        },
        {
          name: "Twice Cooked Pork",
          paragraph:
            "Eget vulputate vitae quis rutrum blandit sed.Quam nulla sit",
          price: "$21",
        },
        {
          name: "Kung Pao Chicken",
          paragraph:
            "Eget vulputate vitae quis rutrum blandit sed.Quam nulla sit",
          price: "$32",
        },
        {
          name: "Char Siu & Sushis",
          paragraph:
            "Eget vulputate vitae quis rutrum blandit sed.Quam nulla sit",
          price: "$48",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
.container .menu-grey {
  padding: 2rem;
  background-color: #e8e8e8;
  line-height: 2rem;
}
.container .menu-black {
  padding: 2rem;
  background-image: url("@/img/misc22x.jpg");
  background-position-y: 100%;
  box-shadow: inset 0px 500px 500px 0px rgba($color: #000000, $alpha: 1);

  background-size: contain;
  color: white;
  line-height: 2rem;
}
.price {
  font-variant: small-caps;
  letter-spacing: 0.1rem;
  font-weight: bold;
}
</style>
