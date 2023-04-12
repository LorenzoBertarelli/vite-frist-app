<script>
export default {
  name: "AppBanner",
  data() {
    return {
      title: "Benvenuti a CVT"
    }
  },
  methods: {

  }
}
</script>

<template>
  <h2> {{ title }} </h2>
  <img class="img-logo" src="../assets/vue.svg" alt="">
</template>

<style>
.img-logo {
    height: 100px;
    width: 120px;
}

h2 {
  color: rgb(17, 0, 255);
}
</style>