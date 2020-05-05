<template>
  <header>
    <headerTopBar></headerTopBar>
    <promo></promo>
  </header>
</template>

<script>
import promo from "~/components/promo.vue";
import headerTopBar from "~/components/headerTopBar.vue";
export default {
  components: {
    promo,
    headerTopBar
  }
};
</script>

<style>
header {
  width: 100vw;
  min-height: 100vh;
  background-color: #131313;
  /* background-image: url(~/static/bcopyg.png);
  background-size: contain;
  background-repeat: no-repeat; */
}
</style>
