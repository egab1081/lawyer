<template>
  <header>
    <div class="header-outer">
      <div class="header-inner">
        <header-top-bar />
        <promo />
      </div>
    </div>
  </header>
</template>

<script>
import promo from "~/components/header/promo.vue";
import headerTopBar from "~/components/header/headerTopBar.vue";
export default {
  components: {
    promo,
    headerTopBar
  }
};
</script>

<style lang="scss" scoped>
header {
  width: 100vw;
  height: 850px;
  background-color: #131313;
  background-image: url(../../assets/bg.png);
  background-size: cover;
  background-repeat: no-repeat;
}
.header {
  &-outer {
    height: 850px;
  }
  &-inner {
    display: flex;
    justify-content: center;
    width: 1153px;
  }
}
</style>
