<script setup>
import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header.vue'

</script>
<template>
  <Header />

  <div class="wrapper">
    <RouterView />
  </div>

  <footer>
    <nav>
      <RouterLink to="/about">關於我們</RouterLink>
      <RouterLink to="/news">最新消息</RouterLink>
      <RouterLink to="/product">產品介紹</RouterLink>
      <RouterLink to="/course">花藝教室</RouterLink>
      <RouterLink to="/space">空間佈置</RouterLink>
      <RouterLink to="/contact">聯絡我們</RouterLink>
    </nav>
  </footer>
</template>

<style scoped lang="scss">
footer {
  width: 100%;
  background-color: #a07b67;

  nav {
    max-width: 1200px;
    margin: auto;
    display: flex;
    justify-content: space-between;
    padding: 30px 0;

    a {
      color: #eee;
    }
  }
}
</style>
