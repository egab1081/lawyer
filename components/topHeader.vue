<template>
  <div class="top-header">
    <headertopbar></headertopbar>
    <div class="right-right">
      <div class="burger"></div>
      <div class="burger"></div>
      <div class="burger"></div>
    </div>
  </div>
</template>

<script>
import headertopbar from "~/components/headertopbar.vue";

export default {
  components: {
    headertopbar
  }
};
</script>
<style>
.top-header {
  margin: 5vh 0 0 0;
  display: flex;
  flex-direction: row;
  justify-content: center;
  color: #fff;
}
.top-header img {
  margin-right: 20px;
}
.top-header h2 {
  font-size: 14px;
  font-weight: normal;
}
</style>