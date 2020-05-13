<template>
  <div>
    <header-main />
    <!-- <easy></easy>
    <numbers></numbers>
    <result></result>
    <meet></meet>
    <city></city>
    <cases></cases>
    <consalt></consalt>
    <footerMain></footerMain>-->
  </div>
</template>

<script>
import headerMain from "~/components/header/headerMain.vue";
// import easy from "~/components/easy/easy.vue";
// import numbers from "~/components/numbers/numbers.vue";
// import result from "~/components/results/result.vue";
// import meet from "~/components/meet.vue";
// import city from "~/components/city.vue";
// import cases from "~/components/cases.vue";
// import consalt from "~/components/consalt.vue";
// import footerMain from "~/components/footer/footerMain.vue";

export default {
  components: {
    headerMain
    // easy,
    // numbers,
    // result,
    // meet,
    // city,
    // cases,
    // consalt,
    // footerMain
  }
};
</script>

<style>
html,
body {
  margin: 0;
  padding: 0;
  width: 100%;
  max-width: 100%;
  overflow-x: hidden;
  font-family: "Tinos", serif;
}
h1,
h2,
p {
  font-weight: normal;
  margin: 0;
  padding: 0;
}
.blue {
  color: #45a4e1;
}
.grey {
  color: #b6b6b6;
}
</style>
