<script setup lang="ts">
import Header from './components/Header.vue'
import Viewport from './components/Viewport.vue'
</script>

<template>
  <div class="body">
    <Header msg="Vite + Vue" />
    <Viewport />>
  </div>
</template>

<style >
.body{
  width: 100%;
  height: 100%;
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
div{
  box-sizing: border-box !important;
}
/* .logo {
  height: 6em;
  padding: 1.5em;
  will-change: filter;
}
.logo:hover {
  filter: drop-shadow(0 0 2em #646cffaa);
}
.logo.vue:hover {
  filter: drop-shadow(0 0 2em #42b883aa);
} */
</style>
