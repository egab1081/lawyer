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
  max-height: 100vh;
  background-color: #131313;
  background-image: url(../assets/bg.png);
  background-size: cover;
  background-repeat: no-repeat;
}
</style>
