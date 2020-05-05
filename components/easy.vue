<template>
  <section class="easy">
    <h1>Простое решение сложных вопросов</h1>
    <div>
      <h2>Для кредиторов</h2>
      <h2>Для должников</h2>
    </div>
    <div>
      <easyHalf></easyHalf>
      <easyHalf></easyHalf>
    </div>
    <div>
      <easyThird></easyThird>
      <easyThird></easyThird>
      <easyThird></easyThird>
    </div>
  </section>
</template>
<script>
import easyHalf from "~/components/easyHalf.vue";
import easyThird from "~/components/easyThird.vue";

export default {
  components: {
    easyHalf,
    easyThird
  }
};
</script>
<style scoped>
.easy h1 {
  text-align: center;
  font-size: 65px;
}
.easy div {
  display: flex;
  flex-direction: row;
  justify-content: center;
}
.easy div h2 {
  margin: 55px 180px;
  font-size: 25px;
  white-space: nowrap;
}
</style>