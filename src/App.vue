<template>
  <div id="app" class="main-contianer">
    <NavBar></NavBar>
    <router-view></router-view>
    <PageBottom></PageBottom>
  </div>
</template>

<script>
import NavBar from "./components/NavBar.vue";
import PageBottom from "./components/PageBottom.vue";

export default {
  name: "app",
  components: {
    NavBar,
    PageBottom,
  },
};
</script>

<style>
</style>
