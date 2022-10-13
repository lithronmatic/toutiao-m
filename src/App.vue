<template>
  <div id="app">
    <!-- 路由的出口 -->
    <router-view/>
    <h1>程序员头条</h1>
    <div>
      <i class="iconfont icon-dianzan2"></i>
    </div>
    <div>
      <van-button type="primary" size="small">主要按钮</van-button>
    </div>
  </div>
</template>

<script>
export default {
  name: 'App'
}
</script>

<style lang="less">

</style>
