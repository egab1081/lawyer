<template>
  <section class="meet-outer">
    <div class="meet-inner">
      <article class="meet-left">
        <h1>
          Давайте знакомиться
          <i>лично</i>
        </h1>
        <p>Меня зовут Андрей Николаевич Прилипко. Мне 29 лет. Я являюсь директором ООО «ГК «Феникс» управляющим партнером «Союза Арбитражных Управляющих». Дважды окончил ПГНИУ по экономической и юридической специальности. Правовая защита бизнеса и активов от команды профессионалов – вот, что вам действительно нужно. Направьте свое время и силы на бизнес. А судами займусь я.</p>
      </article>
      <div class="meet-right">
        <button>
          <!-- <img src="../assets/play.png" alt /> -->
        </button>
        <p class="bg-light">
          <b>Посмотрите видео</b>
        </p>
        <p class="bg-grey grey">
          чтобы узнать больше
          <br />о нашей работе
        </p>
      </div>
    </div>
  </section>
</template>

<script>
</script>

<style scoped>
.meet {
  width: 100vw;
  background-image: url(../assets/5.png);
  background-repeat: no-repeat;
  color: #fff;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  height: 780px;
}
.meet-inner {
  width: 1136px;
}
.meet-left {
  width: 400px;
}
.meet-left h1 {
  font-size: 64px;
  line-height: 65px;
  margin-bottom: 50px;
}
.meet-left p {
  font-size: 19px;
  line-height: 30px;
}
.meet-right p {
  font-size: 17px;
}
.bg-light {
  background-color: #fbfdff;
  color: #000;
  width: 160px;
  border-radius: 2px;
}
.bg-grey {
  background-color: #fff;
  width: 200px;
  border-radius: 2px;
}
button {
  outline: none;
  background-image: url(../assets/play.png);
  padding: 100px;
  background-color: transparent;
  border: 0;
}
</style>