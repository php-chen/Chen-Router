<template>
  <div class="about">
    <h1>这里是子路由的父页面</h1>
    <button @click="onBtn">跳转子路由</button>
    <span>-------------------</span>
    <router-link to="about/test">跳转子路由</router-link>
    <hr>
    <!-- 下面这个标签是用来跳转到子路由的 -->
    <!-- 下面这个标签是用来渲染子路由的 -->
    <router-view />
  </div>
</template>

<script>
export default {
  methods: {
    onBtn() {
      console.log(1);
      // this.$router.push('about/test')
      this.$router.replace('about/test')
    }
  }
}
</script>