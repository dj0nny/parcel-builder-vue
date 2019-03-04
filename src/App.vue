<template>
  <div class="container">
    <Header/>
  </div>
</template>

<script>
import Header from "./components/Header.vue";

export default {
  name: "App",
  components: {
    Header
  }
};
</script>

<style lang="scss">
@import url("https://fonts.googleapis.com/css?family=Montserrat");

body {
  font-family: "Montserrat";
  margin: 0;
  padding: 0;
}
</style>
