<template>
  <div id="app">
    <Header />
    <MainContent />
    <Sidebar />
  </div>
</template>

<script setup>
import Header from "./components/Header.vue";
import Sidebar from "./components/Sidebar.vue";
import MainContent from "./components/MainContent.vue";
</script>

<style>
#app {
  display: flex;
  height: 100vh;
}

Header {
  flex: 0 0 25%;
}

MainContent {
  flex: 0 0 50%;
}

Sidebar {
  flex: 0 0 25%;
}
</style>
