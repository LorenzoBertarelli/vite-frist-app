<script>
import AppBanner from './components/AppBanner.vue';

export default {
  components: {
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
  <AppBanner></AppBanner>
</template>

<style>
h1 {
  color: red;
}
</style>


<!-- <script setup>
import HelloWorld from './components/HelloWorld.vue'
</script>

<template>
  <div>
    <a href="https://vitejs.dev" target="_blank">
      <img src="/vite.svg" class="logo" alt="Vite logo" />
    </a>
    <a href="https://vuejs.org/" target="_blank">
      <img src="./assets/vue.svg" class="logo vue" alt="Vue logo" />
    </a>
  </div>
  <HelloWorld msg="Vite + Vue" />
</template>

<style scoped>
.logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
  transition: filter 300ms;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
}
</style> -->
