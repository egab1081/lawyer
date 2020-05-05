<template>
  <header>
    <topHeader></topHeader>
    <promo></promo>
  </header>
</template>

<script>
import promo from "~/components/promo.vue";
import topHeader from "~/components/topHeader.vue";
export default {
  components: {
    promo,
    topHeader
  }
};

export default {
  components: {
    topHeader
  }
};
</script>

<style>
header {
  width: 100vw;
  min-height: 100vh;
  background-image: url(~~/assets/bcopyg.png);
  background-size: contain;
  background-repeat: no-repeat;
}
</style>
