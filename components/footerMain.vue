<template>
  <footer>
    <footerLeft></footerLeft>
    <footerThird></footerThird>
    <footerThird></footerThird>
  </footer>
</template>

<script>
import footerLeft from "~/components/footerLeft.vue";
import footerThird from "~/components/footerThird.vue";
export default {
  components: {
    footerLeft,
    footerThird
  }
};
</script>

<style scoped>
footer {
  background-color: #252529;
  color: #fff;
  display: flex;
  flex-direction: row;
  justify-content: space-evenly;
  height: 520px;
}
</style>