<script>
import BasicComp from "./components/BasicComp.vue";
export default {
  name: "App",
  components: {
    BasicComp,
  },
};
</script>

<template>
  <BasicComp />
</template>

<style lang="scss">
@use "./styles/general.scss";
body {
  background-color: #121212;
  color: aliceblue;
  text-align: center;
  padding: 3rem;
}
</style>
