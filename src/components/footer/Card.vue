<template>
  <div class="card display-flex">
    <div class="image">
      <img :src="card.image" />
    </div>
    <p>{{ card.text }}</p>
  </div>
</template>

<script>
export default {
  name: "Card",
  props: {
    card: Object,
  },
};
</script>

<style lang="scss" scoped>
.card {
  .image {
    width: 50px;
    height: 50px;
    
    img {
      width: 100%;
      height: 100%;
      object-fit: contain;
    }
  }

  p {
    margin-left: 10px;
    color: #fff;
    text-transform: uppercase;
    font-size: 15px;
  }
}
</style>
