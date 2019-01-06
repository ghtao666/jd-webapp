<template>
  <div class="tgh-header">
    <i class="iconfont icon-jingdong"></i>

    <van-search v-model="value" background="#e83632" placeholder="请输入搜索关键词" show-action @search="onSearch">
      <div slot="action" @click="onSearch">搜索</div>
    </van-search>
  </div>
</template>


<script>
export default {};
</script>

<style lang="less">
@color: #e83632;
.tgh-header {
  display: flex;
  align-items: center;
  justify-content: flex-start;
  .icon-jingdong {
    display: block;
    background-color: @color;
    height: 44px;
    line-height: 44px;
    padding-left: 10px;
    padding-right: 10px;
    color:#fff;
  }
  .van-search {
    flex: 1;
    padding-left: 0px;
    .van-search__action{
      color:#fff;
    }
  }
}
</style>

