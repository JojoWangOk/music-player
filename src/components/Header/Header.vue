<template>
  <div class="cm-header">
    <span class="logo"></span>
    <div class="nav-handler">
      <span class="pre btn-icon"></span>
      <span class="next btn-icon"></span>
    </div>
    <div class="search-box">
      <input type="text" placeholder="搜索音乐，歌手，歌词，用户">
      <i class="search-icon btn-icon"></i>
    </div>
  </div>
</template>

<script>
  export default{}
</script>

<style lang="less" scoped>
  .cm-header {
    background: #c62e3e;
    height: 50px;
    display: flex;
    align-items: center;
    padding-left: 15px;
  }

  .nav-handler {
    border: 1px solid rgba(0, 0, 0, 0.1);
    border-radius: 4px;
    display: flex;
    margin-left: 63px;
    height: 22px;
  }

  .pre {
    border-right: 1px solid rgba(0, 0, 0, 0.1);
  }

  .search-box {
    margin-left: 10px;
    background: rgba(0, 0, 0, 0.2);
    height: 22px;
    width: 218px;
    border-radius: 11px;
    display: flex;
    /*align-items: center;*/

  }

  input {
    background: none;
    outline: none;
    padding-left: 12px;
    color: #F5F5F5;
    height: 22px;
    line-height: 22px;
    width: 195px;
    font-size: 12px;
  }

  .search-icon {
    margin-top: 4px;
  }

  input::-webkit-input-placeholder, textarea::-webkit-input-placeholder {
    color: #c77373;
  }

  input:-moz-placeholder, textarea:-moz-placeholder {
    color: #c77373;
  }

  input::-moz-placeholder, textarea::-moz-placeholder {
    color: #c77373;
  }

  input:-ms-input-placeholder, textarea:-ms-input-placeholder {
    color: #c77373;
  }
</style>
