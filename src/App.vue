<template>
  <div class="app">
    <!-- 路由的出口 -->
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'APP',
  date () {
    return {}
  }
}
</script>

<style scoped>
.app {
  height: 100%;
}
</style>
