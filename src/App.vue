<template>
  <div id="app">
    <CmHeader></CmHeader>
    <div class="content">
      <LeftContent></LeftContent>
      <div class="right-content">
        <router-view></router-view>
      </div>
    </div>
    <CmFooter></CmFooter>
  </div>
</template>

<script>
  import CmHeader from './components/Header/Header'
  import LeftContent from './components/LeftContent/LeftContent'
  import CmFooter from './components/Footer/Footer'
export default {
  name: 'app',
  components: {
    CmHeader,
    LeftContent,
    CmFooter
  }
}
</script>
<style lang="less">
  @import "./style/commom.less";
  @import "./style/sprite.less";
  #app{
    width: 1023px;
    height: 670px;
    margin: 50px auto;
    padding: 0;
    box-shadow: 0 0 10px 7px #e1e1e2;
    background: #ffffff;
  }
  .content{
    height: 572px;
    width: 100%;
    display: flex;
    .right-content{
      width: 823px;
      height: 572px;
      overflow-y: scroll;
    }
  }
</style>
