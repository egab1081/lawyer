<template>
  <footer>
    <div class="footer-outer">
      <div class="footer-inner">
        <footerLeft></footerLeft>
        <footerThird></footerThird>
        <footerThird></footerThird>
      </div>
    </div>
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
.footer-inner {
  width: 937px;
}
</style>