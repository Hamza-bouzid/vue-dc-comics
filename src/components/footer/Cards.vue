<template>
  <div class="cards">
    <div class="container display-flex">
      <Card />
      <Card />
      <Card />
      <Card />
      <Card />
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
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/partials/variables.scss";

.cards {
  background-color: $color-primary;
}

.container {
  padding: 30px 0px;
  justify-content: space-around;
}
</style>
