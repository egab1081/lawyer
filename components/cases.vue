<template>
  <section class="cases">
    <div class="head">
      <h1>Кейсы - лучший рассказ</h1>
      <h1 class="blue">о наших победах</h1>
    </div>
    <div class="btn">
      <button class="btn-grey"></button>
      <button class="btn-blue"></button>
    </div>
    <div class="cases-slider"></div>
  </section>
</template>

<script>
</script>

<style scoped>
h1 {
  font-size: 69px;
  text-align: center;
}
.btn {
  display: flex;
  flex-direction: row;
  position: relative;
  top: -100px;
  left: 1000px;
}
.btn-grey {
  outline: none;
  background-image: url(../assets/7.png);
  background-position: 0 20px;
  padding: 50px;
  background-color: transparent;
  border: 0;
}
.btn-blue {
  outline: none;
  background-image: url(../assets/8.png);
  padding: 50px;
  background-color: transparent;
  border: 0;
}
</style>