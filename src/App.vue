<script>
import AppTitle from './components/AppTitle.vue'
import AppBanner from './components/AppBanner.vue';

export default {
  components: {
    AppTitle,
    AppBanner
  },
  data() {
    return {
      title: "My title"
    }
  }
}
</script>

<template>
  <h1>Hello Vue with Vite {{ title }}</h1>
  <AppTitle></AppTitle>
  <AppBanner></AppBanner>
</template>

<style>
h1 {
  color: red;
}
</style>