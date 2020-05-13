<template>
  <div class="promo">
    <div class="promo-left">
      <div class="expert">
        <h1>Экспертные услуги</h1>
        <h1>по банкротству</h1>
        <h1 class="blue">физических лиц</h1>
        <h1 class="blue">и бизнеса</h1>
      </div>
      <h2>
        Бесплатный правовой анализ вашей
        <br />проблемы от арбитражного
        управляющего
      </h2>
      <div class="image">
        <div class="analise">
          <a href>ПОЛУЧИТЬ АНАЛИЗ</a>
        </div>
        <img class="paper" src="~assets/L.png" alt />
        <img class="print" src="~assets/print.png" alt />
      </div>
      <p>
        Ответьте на 5 вопросов и получите
        <br />правовой анализ проблемы от
        <br />арбитражного упраавляющего
      </p>
    </div>
    <promoRight></promoRight>
  </div>
</template>

<script>
import promoRight from "~/components/header/promoRight.vue";
export default {
  components: {
    promoRight
  }
};
</script>

<style lang="scss" scoped>
.promo {
  display: flex;
  flex-direction: row;
  justify-content: space-around;
  color: #fff;
}
.promo img {
  position: relative;
  z-index: -1;
}
.promo-left {
  max-width: 570px;
  max-height: 600px;
}
.promo-left h1 {
  font-size: 68px;
  white-space: nowrap;
}
.promo-left h2 {
  font-size: 20px;
  margin-bottom: 65px;
}

.analise {
  display: flex;
  justify-content: center;
  max-width: 290px;
  max-height: 100px;
  border: 1px solid #45a4e1;
  background-color: #45a4e1;
  border-radius: 10px;
  margin-bottom: 40px;
}
.analise a {
  font-size: 17px;
  color: #fff;
  text-decoration: none;
  margin: 40px 20px 50px 20px;
}
.paper {
  position: relative;
  top: -170px;
  left: 280px;
}
.print {
  position: relative;
  top: -210px;
  left: 230px;
}
.promo-left p {
  font-size: 17px;
  font-style: bold italic;
}
.expert {
  margin-bottom: 40px;
  font-size: 68px;
}
</style>
