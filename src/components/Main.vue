<template>
  <main>
    <Jumbo />
    <Comics />
  </main>
</template>
<script>

import Jumbo from "./main/Jumbo.vue";
import Comics from "./main/Comics.vue";

export default {
  name: "Main",
  components: {
    Jumbo,
    Comics
    
  },
};
</script>

<style lang="scss" scoped>

</style>
