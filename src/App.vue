<script setup lang="ts">
import Guest from './pages/guest/Home.vue'
</script>

<template>
  <Guest />
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
.page_body{
    padding: 14px 114px;
    width: 100%;
    display: flex;
    align-items: flex-start;
}
.page_body_main{
  flex: 1 1 70%;
  padding: 8px;
}
.page_body_side{
  flex: 1 1 30%;
  display: block;
  min-height: 100vh;
  position: sticky;
  top: 0;
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
