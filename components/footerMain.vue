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
</style>