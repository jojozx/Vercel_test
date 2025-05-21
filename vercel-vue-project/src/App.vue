<script setup>
// @/是src目录的别名，通常在vite.config.js中配置，但此处我们直接使用相对路径
import HomePage from './components/HomePage.vue';
</script>

<template>
  <HomePage />
</template>

<style>
/* 在这里可以添加一些全局样式 */
body {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
}

#app {
  /* 确保应用填满整个视口 */
  min-height: 100vh;
  display: flex;
  flex-direction: column;
}
</style>
