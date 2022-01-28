<template>
  <footer>
    <Cards />
    <Links />
    <Social />
  </footer>
</template>

<script>
import Cards from "./footer/Cards.vue";
import Links from "./footer/Links.vue";
import Social from "./footer/Social.vue";

export default {
  name: "Footer",
  components: {
    Cards,
    Links,
    Social,
  },
};
</script>

<style lang="scss" scoped></style>
