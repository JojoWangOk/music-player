<template>
  <div id="app">
    <Headers></Headers>
    <router-view></router-view>
  </div>
</template>

<script>
  import Headers from './components/Header/Header'

export default {
  name: 'app',
  components: {
    Headers,
  }
}
</script>
<style lang="less" scoped>
  @import "./style/commom.less";
  @import "./style/sprite.less";
  #app{
    width: 1020px;
    height: 670px;
    margin: 50px auto;
    padding: 0;
    box-shadow: 0 0 10px 7px #e1e1e2;
  }
</style>
