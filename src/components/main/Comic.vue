<template>
  <div class="comic">
    <div class="comic-img">
      <img :src="comic.thumb" />
    </div>
    <span>{{ comic.series }}</span>
  </div>
</template>

<script>
export default {
  name: "Comic",
  props: {
    comic: Object,
  },
};
</script>

<style lang="scss" scoped>
.comic {
  padding: 15px 0px;
  width: 180px;
  height: 250px;

  &-img {
    width: 180px;
    height: 180px;
    overflow: hidden;
    margin-bottom: 15px;
  }
  span {
    text-transform: uppercase;
    color: #fff;
  }
}
</style>
