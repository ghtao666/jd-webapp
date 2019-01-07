<template>
  <div class="tgh-header">
    <div class="header">
      <i class="iconfont icon-jingdong"></i>

      <van-search background="#e83632" placeholder="笔记本" show-action>
        <div slot="action">搜索</div>
      </van-search>
    </div>
  </div>
</template>


<script>
export default {};
</script>

<style lang="less">
@color: #e83632;
.tgh-header {
  position: fixed;
  top: 0px;
  left: 0px;
  z-index: 9999;
  width: 100%;
  .header {
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
      color: #fff;
      font-size: 16px;
    }
    .van-search {
      flex: 1;
      padding-left: 0px;
      .van-search__action {
        color: #fff;
      }
    }
  }
}
</style>

