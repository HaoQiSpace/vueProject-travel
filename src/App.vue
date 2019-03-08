<template>
  <div id="app">
    <!-- exclude="Detail"：使得进入Detail页面不会被缓存，从而需要新发取ajax数据请求 -->
    <keep-alive exclude="Detail">
      <router-view/>
    </keep-alive>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style></style>
