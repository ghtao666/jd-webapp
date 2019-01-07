<template>
  <div class="tgh-tabbar">
    <van-tabbar v-model="active" active-color="#e83632">
      <van-tabbar-item>
        <span>首页</span>
        <i
          slot="icon"
          slot-scope="props"
          :class="['iconfont',props.active?'icon-homefill':'icon-home']"
        ></i>
      </van-tabbar-item>

      <van-tabbar-item>
        <span>分类</span>
        <i
          slot="icon"
          slot-scope="props"
          :class="['iconfont',props.active?'icon-fenleih':'icon-fenlein']"
        ></i>
      </van-tabbar-item>

      <van-tabbar-item>
        <span>购物车</span>
        <i
          slot="icon"
          slot-scope="props"
          :class="['iconfont',props.active?'icon-cartfill':'icon-cart']"
        ></i>
      </van-tabbar-item>

      <van-tabbar-item>
        <span>我的</span>
        <i
          slot="icon"
          slot-scope="props"
          :class="['iconfont',props.active?'icon-peoplefill':'icon-people']"
        ></i>
      </van-tabbar-item>
    </van-tabbar>
  </div>
</template>


<script>
export default {
  data() {
    return {
      active: 0
    };
  }
};
</script>

<style lang="less">
.tgh-tabbar {
  .van-tabbar {
    max-width: 750PX;//大写PX
    left: 50%;
    transform: translateX(-50%);
    .iconfont {
      font-size: 20px;
    }
  }
}
</style>
