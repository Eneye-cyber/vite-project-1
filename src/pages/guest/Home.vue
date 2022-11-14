<script setup lang="ts">
import Header from '../../components/guest/Header.vue'
import Viewport from '../../components/guest/Viewport.vue'
import Trending from '../../components/guest/Trending.vue'
import Articles from './../../components/guest/Articles.vue'
import Categories from '../../components/guest/Categories.vue'
</script>

<template>
  <div class="body">
    <Header msg="Vite + Vue" />
    <Viewport />
    <Trending />
    <div class="page_body">
      <div class="page_body_main container">
        <Articles />
      </div>
      <div class="page_body_side container">
        <Categories />
      </div>
    </div>
  </div>
</template>

<style scoped>
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
@media only screen and (max-width: 1080px) {
  .page_body{
    padding: 14px 0;
    width: 100%;
    flex-direction: column-reverse;
  }
  .page_body_main, .page_body_side{
    border-bottom: 1px solid rgba(0, 0, 0, 0.1);
    padding-bottom: 0 !important;
    flex: 1 0 100%;
    min-width: 100%;
    min-height: auto;
    position: relative;
  }
  .page_body_side{
    flex: 1 0 100%;
    min-width: 100%;
    min-height: auto;
    position: relative;
  }
}
</style>
