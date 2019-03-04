<template>
  <div class="header-container">
    <h1>{{message}}</h1>
    <img src="../assets/front.png">
  </div>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      message: "Parcel + Vue.js"
    };
  }
};
</script>

<style lang="scss" scoped>
.header-container {
  text-align: center;
  img {
    width: 50%;
  }
}
</style>
