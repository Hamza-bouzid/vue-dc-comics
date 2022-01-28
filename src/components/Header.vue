<template>
  <header>
    <div class="hb-container display-flex">
      <div class="logo">
        <a href="#"><img src="../assets/img/dc-logo.png" /></a>
      </div>
      <nav>
        <ul>
          <li v-for="(link, index) in links" :key="index">
            <a :class="{active: link.current}" :href="link.url">{{ link.text }}</a>
          </li>
        </ul>
      </nav>
    </div>
  </header>
</template>
<script>
export default {
  name: "Header",
  data() {
    return {
      links: [
        {
          text: "Characters",
          url: "#",
          current: false,
        },
        {
          text: "Comics",
          url: "#",
          current: true,
        },
        {
          text: "Movies",
          url: "#",
          current: false,
        },
        {
          text: "Tv",
          url: "#",
          current: false,
        },
        {
          text: "Games",
          url: "#",
          current: false,
        },
        {
          text: "Collectibles",
          url: "#",
          current: false,
        },
        {
          text: "Videos",
          url: "#",
          current: false,
        },
        {
          text: "Fans",
          url: "#",
          current: false,
        },
        {
          text: "News",
          url: "#",
          current: false,
        },
        {
          text: "Shop",
          url: "#",
          current: false,
        },
      ],
    };
  },
};
</script>

<style lang="scss" scoped>
@import "../assets/style/partials/variables.scss";

.hb-container {
  padding: 20px 0px;
  justify-content: space-between;
}


.logo img {
  width: 80px;
}

nav {
  ul li {
    display: inline-block;
    list-style: none;

    a {
      text-decoration: none;
      color: #000;
      padding: 0px 15px;
      text-transform: uppercase;
      font-size: 12px;
      font-weight: bold;

      &:hover,
      &.active {
        color: $color-primary;
      }
    }
  }
}
</style>
