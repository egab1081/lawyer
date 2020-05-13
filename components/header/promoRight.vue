<template>
  <div class="promo-right">
    <div class="promo-right_top">
      <h1>Андрей Прилипко</h1>
      <p class="grey">Управляющий партнер «Союза Арбитражных Управляющих»</p>
    </div>
    <article class="promo-right_bottom">
      <p>
        <b class="f18">Мы пишем сценарий</b>
        <br />для самых сложных банкротных дел
      </p>
    </article>
  </div>
</template>

<script>
</script>

<style lang="scss" scoped>
.promo-right_top {
  display: flex;
  flex-direction: column;
  max-width: 180px;
  margin-left: 50px;
}
.promo-right_top h1 {
  font-size: 20px;
  margin-bottom: 15px;
}
.promo-right_top p {
  font-size: 15px;
  margin-bottom: 70px;
}
.promo-right_bottom {
  min-width: 230px;
  min-height: 340px;
  width: 230px;
  height: 340px;
  background-image: url(../../assets/1pen.png);
  background-repeat: no-repeat;
  display: flex;
  justify-content: center;
  text-align: center;
  line-height: 25px;
  color: #000;
}
.promo-right_bottom p {
  margin-top: 120px;
  line-height: 25px;
  max-width: 135px;
  font-size: 17px;
}
</style>