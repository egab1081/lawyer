<template>
  <section class="result-outer">
    <div class="result-inner">
      <img src="../assets/magazine.png" alt />
      <h1>Добиваемся результатов</h1>
      <h1 class="blue">не только на бумаге</h1>
      <div>
        <ol>
          <li class="active">
            <b class="f19">Все начинается с претензиозной работы</b> наш принцип - суд только
            после переговоров, у нас есть аргументы для должников
          </li>
          <li class="normal">
            <b class="f19">Все начинается с претензиозной работы</b> наш принцип - суд только
            после переговоров, у нас есть аргументы для должников
          </li>
          <li class="normal">
            <b class="f19">Все начинается с претензиозной работы</b> наш принцип - суд только
            после переговоров, у нас есть аргументы для должников
          </li>
          <li class="normal">
            <b class="f19">Все начинается с претензиозной работы</b> наш принцип - суд только
            после переговоров, у нас есть аргументы для должников
          </li>
        </ol>
        <result-right />
      </div>
    </div>
  </section>
</template>

<script>
import resultRight from "~/components/resultRight.vue";

export default {
  components: {
    resultRight
  }
};
</script>

<style scoped>
.result {
  background-color: #fbfbfb;
  position: relative;
  z-index: 1;
}
.result-inner {
  width: 1064px;
}
img {
  position: absolute;
  z-index: -1;
  bottom: -360px;
  right: 0px;
  visibility: hidden;
}
div {
  display: flex;
  flex-direction: row;
  justify-content: center;
}
ol {
  margin: 0;
}
h1 {
  font-size: 69px;
  margin-left: 170px;
}
li {
  font-size: 19px;
  width: 450px;
  margin-top: 30px;
  line-height: 30px;
}
.f19 {
  font-size: 20px;
}
.normal {
  list-style: none;
  background: url(../assets/list-circle.png) no-repeat 0 2px;
  padding-left: 70px;
}
.active {
  list-style: none;
  background: url(../assets/list-circle-active.png) no-repeat 0 2px;
  padding-left: 70px;
}
</style>