<template>
  <div class="cards">
    <div class="hb-container display-flex">
      <Card v-for="(elem, index) in cards" :key="index" :card="cards[index]" />
    </div>
  </div>
</template>

<script>
import Card from "./Card.vue";

export default {
  name: "Cards",
  components: {
    Card,
  },

  data() {
    return {
      cards: [
        {
          image: require("../../assets/img/buy-comics-digital-comics.png"),
          text: "Digital Comics",
        },
        {
          image: require("../../assets/img/buy-comics-merchandise.png"),
          text: "Dc merchandise",
        },
        {
          image: require("../../assets/img/buy-comics-subscriptions.png"),
          text: "Subscription",
        },
        {
          image: require("../../assets/img/buy-comics-shop-locator.png"),
          text: "Comic shop location",
        },
        {
          image: require("../../assets/img/buy-dc-power-visa.svg"),
          text: "Dc power visa",
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/partials/variables.scss";

.cards {
  background-color: $color-primary;
}

.hb-container {
  padding: 30px 0px;
  justify-content: space-around;
}
</style>
