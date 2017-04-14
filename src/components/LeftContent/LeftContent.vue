<template>
  <div class="left-content">
    <p class="type-title">推荐</p>
    <router-link :to="'home'" class="link-item"><i class="music"></i>发现音乐</router-link>
    <router-link :to="''" class="link-item"><i class="fm"></i>私人FM</router-link>
    <router-link :to="''" class="link-item"><i class="mv"></i>MV</router-link>
    <router-link :to="''" class="link-item"><i class="friend"></i>朋友</router-link>
    <p class="type-title">我的音乐</p>
    <router-link :to="'home'" class="link-item"><i class="local_music"></i>本地音乐</router-link>
    <router-link :to="''" class="link-item"><i class=download></i>下载管理</router-link>
    <p class="type-title">创建歌单</p>
    <router-link :to="'home'" class="link-item"><i class="heart"></i>我喜欢的音乐</router-link>
  </div>
</template>

<script>
  export default{

  }
</script>

<style lang="less" scoped>
  .left-content{
    width: 200px;
    background: #f5f5f7;
    overflow-y: scroll;
    border-right: 1px solid #e1e1e2;
  }
  .type-title{
    color: #7d7d7d;
    line-height: 32px;
    padding-left: 10px;
  }
  .link-item{
    display: flex;
    height: 32px;
    align-items: center;
    padding-left: 16px;
    color: #5c5c5c;
    border-left: 3px solid #f5f5f7;
      i{
        margin-right: 11px;
      }
  }
  .link-item.router-link-active{
    color: #333333;
    background: #e6e7ea;
    border-left: 3px solid #c62f2f;
  }

</style>
