<template>
  <div class="tgh-header">
    <div class="header">
      <i class="iconfont icon-fenleisvg"></i>

      <div class="search-container">
        <i class="iconfont icon-jingdong van-hairline--right"></i>
        <i class="iconfont icon-sousuo1"></i>
        <span class="search-text">笔记本</span>
      </div>

      <span class="login-text">登录</span>
    </div>
  </div>
</template>


<script>
export default {
  data() {},
  mounted() {
    window.onscroll = () => {
      let scrollTop =
        document.documentElement.scrollTop || document.body.scrollTop;
      if (scrollTop < 120) {
        document.querySelector(".tgh-header").style.backgroundColor =
          "transparent";
      } else {
        document.querySelector(".tgh-header").style.backgroundColor = "#e83632";
      }
    };
  }
};
</script>

<style lang="less">
@color: #e83632;

.tgh-header {
  max-width: 750PX;//大写PX
  position: fixed;
  top: 0px;
  left: 50%;
  transform: translateX(-50%);
  z-index: 9999;
  width: 100%;
  background-color: transparent;
  .header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    color: #fff;
    height: 44px;
    .icon-fenleisvg {
      margin-left: 10px;
      margin-right: 10px;
    }
    .search-container {
      flex: 1;
      height: 32px;
      background-color: #fff;
      border-radius: 50px;
      display: flex;
      align-items: center;
      .icon-jingdong {
        color: @color;
        display: inline-block;
        text-align: center;
        font-size: 18px;
        font-weight: bold;
        width: 35px;
        margin-left: 10px;
      }
      .icon-sousuo1 {
        color: #c0c4cc;
        display: inline-block;
        text-align: center;
        font-size: 14px;
        width: 35px;
      }
      .search-text {
        color: #c0c4cc;
        display: inline-block;
        font-size: 14px;
      }
    }
    .login-text {
      font-size: 14px;
      margin-left: 10px;
      margin-right: 10px;
    }
  }
}
</style>

