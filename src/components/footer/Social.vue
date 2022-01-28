<template>
  <div class="social">
    <div class="hb-container">
      <div class="cta">
        <a href="#">Sign-up now!</a>
      </div>

      <div class="social-links">
        <a href="#">Follow us</a>
        <a href="#"><img src="../../assets/img/footer-facebook.png" /></a>
        <a href="#"><img src="../../assets/img/footer-twitter.png" /></a>
        <a href="#"><img src="../../assets/img/footer-youtube.png" /></a>
        <a href="#"><img src="../../assets/img/footer-pinterest.png" /></a>
        <a href="#"><img src="../../assets/img/footer-periscope.png" /></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Social",
};
</script>

<style lang="scss" scoped>
@import "../../assets/style/partials/variables.scss";

.hb-container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.social {
  background-color: #303030;
  padding: 40px 0px;
}

.cta {
  a {
    color: #fff;
    text-decoration: none;
    text-transform: uppercase;
    padding: 5px 10px;
    border: 2px solid $color-primary;
  }
}

.social-links {
  display: flex;
  align-items: center;
  a {
    color: $color-primary;
    text-decoration: none;
    text-transform: uppercase;
    margin: 0px 5px;
  }

  img {
    width: 30px;
  }
}
</style>
