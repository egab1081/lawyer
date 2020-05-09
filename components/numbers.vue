<template>
  <section class="numbers">
    <h1>Цифры говорят о нас</h1>
    <div>
      <numbersThird></numbersThird>
      <numbersCenter></numbersCenter>
      <numbersThird></numbersThird>
    </div>
  </section>
</template>

<script>
import numbersThird from "~/components/numbersThird.vue";
import numbersCenter from "~/components/numbersCenter.vue";

export default {
  components: {
    numbersThird,
    numbersCenter
  }
};
</script>

<style scoped>
.numbers {
  margin-bottom: 80px;
}
h1 {
  font-size: 69px;
  text-align: center;
  margin-bottom: 30px;
}
div {
  display: flex;
  flex-direction: row;
}
.f18 {
  font-size: 18px;
}
</style>