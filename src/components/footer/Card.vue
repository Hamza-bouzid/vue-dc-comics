<template>
  <div class="card display-flex">
    <img src="../../assets/img/buy-comics-digital-comics.png" />
    <p>Digital Comics</p>
  </div>
</template>

<script>
export default {
  name: "Card",
};
</script>

<style lang="scss" scoped>
.card {
  img {
    width: 50px;
  }

  p {
    margin-left: 10px;
    color: #fff;
    text-transform: uppercase;
    font-size: 15px;
  }
}
</style>
