<template>
  <div id="app">
    <router-view></router-view>
   <main-tab-bar></main-tab-bar>
  </div>
</template>

<script>
import MainTabBar from './components/content/MainTabBar.vue'
import MainTabBar from './components/content/MainTabBar/MainTabBar.vue'
  export default {
    name: 'app',
    components: {
      MainTabBar,
        MainTabBar
    }
  }
</script>

<style>
@import "./assets/css/base.css";


</style>
