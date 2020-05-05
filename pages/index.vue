<template>
  <headerMain></headerMain>
</template>

<script>
import headerMain from "~/components/headerMain.vue";

export default {
  components: {
    headerMain
  }
};
</script>

<style>
html,
body {
  margin: 0;
  padding: 0;
  max-width: 100vw;
  min-height: 100vh;
  font-family: "Tinos", serif;
}

h1,
h2,
p {
  font-weight: normal;
  margin: 0;
  padding: 0;
}
</style>
