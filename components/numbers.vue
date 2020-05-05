<template>
  <section class="numbers">
    <h1>Цифры говорят о нас</h1>
    <div>
      <numbersThird></numbersThird>
      <numbersThird></numbersThird>
      <numbersThird></numbersThird>
    </div>
  </section>
</template>

<script>
import numbersThird from "~/components/numbersThird.vue";

export default {
  components: {
    numbersThird
  }
};
</script>

<style scoped>
</style>