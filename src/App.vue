<template>
  <div id="app">
    <main-tab-bar></main-tab-bar>
  </div>
</template>

<script>
import MainTabBar from "components/content/mainTabbar/MainTabBar";

export default {
  name: "App",
  components: {
    MainTabBar
  },
  methods: {
    test() {
      console.log("zzzzz");
    }
  }
};
</script>

<style>
@import "assets/css/base.css";
</style>
