<template>
  <div class="home">
    <tgh-header></tgh-header>

    <!-- 轮播图 -->
    <van-swipe :autoplay="3000" indicator-color="white">
      <van-swipe-item>
        <img src="//gw.alicdn.com/imgextra/i4/173/O1CN01G63dIF1D9H0f9S5Eg_!!173-0-lubanu.jpg" alt>
      </van-swipe-item>

      <van-swipe-item>
        <img src="//gw.alicdn.com/imgextra/i1/72/O1CN01Ypa8Sr1CP10UQZXOJ_!!72-0-lubanu.jpg" alt>
      </van-swipe-item>

      <van-swipe-item>
        <img src="//gw.alicdn.com/imgextra/i4/121/O1CN01BRkXNc1ClSPnFdikI_!!121-0-lubanu.jpg" alt>
      </van-swipe-item>

      <van-swipe-item>
        <img src="https://aecpm.alicdn.com/simba/img/TB15tIjGVXXXXcoapXXSutbFXXX.jpg" alt>
      </van-swipe-item>
    </van-swipe>

    <div class="nav-container">
      <div class="nav">
        <img
          src="//m.360buyimg.com/mobilecms/s120x120_jfs/t1/28589/13/4137/14657/5c2eff13Ede233fc5/dc2502750258053e.png"
          alt
        >
        <span>京东超市</span>
      </div>
      <div class="nav">
        <img
          src="//m.360buyimg.com/mobilecms/s120x120_jfs/t26635/320/1832919204/11533/a2f9878a/5bee366dN1627d554.png"
          alt
        >
        <span>海囤全球</span>
      </div>

      <div class="nav">
        <img
          src="//m.360buyimg.com/mobilecms/s120x120_jfs/t1/17169/3/4127/4611/5c2f35cfEd87b0dd5/65c0cdc1362635fc.png"
          alt
        >
        <span>京东服饰</span>
      </div>

      <div class="nav">
        <img
          src="//m.360buyimg.com/mobilecms/s120x120_jfs/t1/27962/13/1445/4620/5c120b24Edd8c34fe/43ea8051bc50d939.png"
          alt
        >
        <span>京东生鲜</span>
      </div>

      <div class="nav">
        <img
          src="//m.360buyimg.com/mobilecms/jfs/t1/9698/26/11922/69392/5c2efc62Ef1ad2c93/46e53c77bccc2f91.gif"
          alt
        >
        <span>京东旅行</span>
      </div>
    </div>

    <div class="nav-container">
      <div class="nav">
        <img
          src="//m.360buyimg.com/mobilecms/s120x120_jfs/t18454/342/2607665324/6406/273daced/5b03b74eN3541598d.png"
          alt
        >
        <span>充值缴费</span>
      </div>
      <div class="nav">
        <img
          src="//m.360buyimg.com/mobilecms/s120x120_jfs/t22228/270/207441984/11564/88140ab7/5b03fae3N67f78fe3.png"
          alt
        >
        <span>9.9元拼</span>
      </div>

      <div class="nav">
        <img
          src="//m.360buyimg.com/mobilecms/s120x120_jfs/t1/7068/29/8987/5605/5c120da2Ecae1cc3a/016033c7ef3e0c6c.png"
          alt
        >
        <span>领券</span>
      </div>

      <div class="nav">
        <img
          src="//m.360buyimg.com/mobilecms/s120x120_jfs/t16828/63/2653634926/5662/d18f6fa1/5b03b779N5c0b196f.png"
          alt
        >
        <span>赚钱</span>
      </div>

      <div class="nav">
        <img
          src="//m.360buyimg.com/mobilecms/s120x120_jfs/t21481/263/412160889/15938/4246b4f8/5b0cea29N8fb2865f.png"
          alt
        >
        <span>全部</span>
      </div>
    </div>

    <!-- 京东快报 -->
    <div class="notice-container">
      <img
        src="//m.360buyimg.com/mobilecms/jfs/t14752/82/2574581467/6535/c8158ace/5aa8935bN94e31ff6.jpg.dpg"
      >
      <van-swipe :autoplay="2000" vertical :show-indicators="false">
        <van-swipe-item class="van-ellipsis">
          <span class="hot">热门</span>
          <span class="content">惊喜不断！92汽油喜迎5连跌哈哈哈</span>
        </van-swipe-item>
        <van-swipe-item class="van-ellipsis">
          <span class="hot">HOT</span>
          <span class="content">论口红的重要性，可盐可甜一唇之隔</span>
        </van-swipe-item>
        <van-swipe-item class="van-ellipsis">
          <span class="hot">热门</span>
          <span class="content">华为正式宣布了，让苹果开始升值</span>
        </van-swipe-item>
        <van-swipe-item class="van-ellipsis">
          <span class="hot">HOT</span>
          <span class="content">金立乐视倒下后，又一国产手机崛起</span>
        </van-swipe-item>
      </van-swipe>

      <span class="more">更多</span>
    </div>

    <!-- 新人红包 -->
    <div class="new-people-container">
      <div>
        <img
          src="//m.360buyimg.com/mobilecms/jfs/t1/24056/17/2005/80908/5c186655E14dc7cf2/820a7029a2540e25.jpg!q70.jpg.dpg"
          alt
        >
      </div>
      <div>
        <img
          src="//m.360buyimg.com/mobilecms/jfs/t1/26685/26/1930/47992/5c186663Ee07857b2/533b3a90ad7aa17b.jpg!q70.jpg.dpg"
          alt
        >
      </div>
      <div>
        <img
          src="//m.360buyimg.com/mobilecms/jfs/t1/27089/22/2030/53621/5c186677Ebbaa20af/bd39d47042dccbaf.jpg!q70.jpg.dpg"
          alt
        >
      </div>
    </div>

    <!-- 京东秒杀 -->
    <div class="seckill-container">
      <div class="seckill-top">
        <div class="seckill-top-left">
          <span class="seckill-text">京东秒杀</span>
          <span class="seckill-time">20点场</span>
        </div>
        <div class="seckill-top-right">
          <span class="more">更多秒杀</span>
          <i class="iconfont icon-you-yuan-tianchong"></i>
        </div>
      </div>
      <div class="seckill-content">
        <div class="seckill-item">
          <img
            src="//img14.360buyimg.com/n1/s150x150_jfs/t29392/172/691516965/253986/e85a9c6f/5bfbc0b7N40b06009.jpg.dpg"
            alt
          >
          <div class="seckill-price">￥4998</div>
          <div class="init-price">￥5399</div>
        </div>

        <div class="seckill-item">
          <img
            src="//img14.360buyimg.com/n1/s150x150_jfs/t11491/11/821570861/133610/1a9048e2/59f92df2N2828fc82.jpg.dpg"
            alt
          >
          <div class="seckill-price">￥2598</div>
          <div class="init-price">￥3399</div>
        </div>

        <div class="seckill-item">
          <img
            src="//img14.360buyimg.com/n1/s150x150_jfs/t18469/162/2592359673/239582/e022adf3/5afaca60N98e14693.jpg.dpg"
            alt
          >
          <div class="seckill-price">￥2698</div>
          <div class="init-price">￥2999</div>
        </div>

        <div class="seckill-item">
          <img
            src="//img14.360buyimg.com/n1/s150x150_jfs/t1/29614/2/3768/179869/5c2c293bE31e3bdc9/1bcb4888ad156a4e.jpg.dpg"
            alt
          >
          <div class="seckill-price">￥288</div>
          <div class="init-price">￥368</div>
        </div>
      </div>
    </div>

    <!-- 分割线---东家小院 -->
    <div class="dong-jia-xiao-yuan">
      <img
        src="//m.360buyimg.com/mobilecms/s750x80_jfs/t25132/272/777079429/42670/e6ced36f/5b7a6fa1N94e7f9d9.jpg!q70.jpg.dpg"
      >
    </div>

    <div class="category-container">
      <div class="category-container-top">
        <div class="category-container-top-item">
          <div class="item-title">奢品大牌</div>
          <div class="item-text">倍有面的大牌推荐</div>
          <div class="item-img-container">
            <div class="item-img">
              <img
                src="//m.360buyimg.com/mobilecms/s150x150_jfs/t17686/280/2553683255/183590/e4816078/5afba52eNc3f33a32.jpg!q70.jpg.dpg"
                alt
              >
            </div>

            <div class="item-img">
              <img
                src="//m.360buyimg.com/mobilecms/s150x150_jfs/t20143/328/95318805/83204/5a0a150e/5afb8ca6Nab4d0336.jpg!q70.jpg.dpg"
                alt
              >
            </div>
          </div>
        </div>
        <div class="category-container-top-item">
          <div class="item-title">秋冬童装</div>
          <div class="item-text">妈妈放心，宝宝舒心</div>
          <div class="item-img-container">
            <div class="item-img">
              <img
                src="//m.360buyimg.com/mobilecms/s150x150_jfs/t1/8682/38/1507/83324/5bce94c1E22084ec9/b762068f6fdbf254.jpg!q70.jpg.dpg"
                alt
              >
            </div>

            <div class="item-img">
              <img
                src="//m.360buyimg.com/mobilecms/s150x150_jfs/t1/8681/24/8792/426436/5c0f6b31E1919de75/d8ca1ebae29286e4.jpg!q70.jpg.dpg"
                alt
              >
            </div>
          </div>
        </div>
      </div>
      <div class="category-container-bottom">
        <div class="category-container-bottom-item">
          <div class="item-title">二手寻宝</div>
          <div class="item-text">跳骚市场</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/mobilecms/s150x150_jfs/t1/20009/16/3914/88712/5c2d0624Ebd486084/4a6fd5aa36b80305.jpg!q70.jpg.dpg"
            >
          </div>
        </div>

        <div class="category-container-bottom-item">
          <div class="item-title">专属鞋柜</div>
          <div class="item-text">随心选鞋</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/mobilecms/s150x150_jfs/t12658/344/788867049/176709/82286472/5a13e0d1Nd28f74aa.jpg!q70.jpg.dpg"
            >
          </div>
        </div>

        <div class="category-container-bottom-item">
          <div class="item-title">时尚女包</div>
          <div class="item-text">潮包更时尚</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/mobilecms/s150x150_jfs/t21457/184/259728036/257739/faf767b5/5b07dd69N168b74c6.jpg!q70.jpg.dpg"
            >
          </div>
        </div>

        <div class="category-container-bottom-item">
          <div class="item-title">早春穿搭</div>
          <div class="item-text">早春抢先购</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/mobilecms/s150x150_jfs/t29929/307/395232908/185564/a514971b/5bf19456N4317061a.jpg!q70.jpg.dpg"
            >
          </div>
        </div>
      </div>
    </div>

    <!-- 分割线---每日逛 -->
    <div class="mei-ri-guang">
      <img
        src="//m.360buyimg.com/mobilecms/s750x80_jfs/t20863/125/519979559/24806/2e941d67/5b0fecc7N541bb0dd.png!q70.jpg.dpg"
      >
    </div>
    <tgh-tabbar></tgh-tabbar>
  </div>
</template>


<script>
import TghHeader from "@/components/tgh-header";
import TghTabbar from "@/components/tgh-tabbar";
export default {
  data() {
    return {};
  },
  components: {
    TghHeader,
    TghTabbar
  }
};
</script>


<style lang="less" >
@color: #f10215;
.home {
  padding-bottom: 100px;
  .van-swipe {
    height: 112px;
    img {
      width: 100%;
    }
  }

  .nav-container {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    flex-wrap: wrap;
    background-color: #fff;
    border-top-left-radius: 10px;
    border-top-right-radius: 10px;
    transform: translateY(-5px);
    padding-top: 10px;
    .nav {
      flex: 1;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: flex-start;
      img {
        width: 40px;
      }
      span {
        font-size: 13px;
        display: inline-block;
        margin-top: 5px;
        color: #666;
      }
    }
  }

  .notice-container {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-top: 5px;
    img {
      width: 73px;
      margin-left: 10px;
      margin-right: 10px;
    }
    .van-swipe {
      flex: 1;
      height: 20px;
      .hot {
        color: @color;
        font-size: 14px;
      }
      .content {
        font-size: 14px;
      }
    }
    span.more {
      margin-right: 10px;
      margin-left: 5px;
      color: #181818;
      font-size: 13px;
    }
  }

  .new-people-container {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    margin-top: 5px;
    margin-bottom: 5px;
    padding-left: 5px;
    padding-right: 5px;
    div {
      flex: 1;
      &:nth-child(1) {
        flex: 2;
      }
      img {
        width: 100%;
      }
    }
  }

  .seckill-container {
    padding-left: 10px;
    padding-right: 10px;
    padding-bottom: 15px;
    .seckill-top {
      display: flex;
      justify-content: space-between;
      align-items: center;
      .seckill-top-left {
        .seckill-text {
          color: @color;
          font-weight: bold;
        }
        .seckill-time {
          font-size: 14px;
          font-weight: bold;
        }
      }

      .seckill-top-right {
        .more {
          font-size: 12px;
          color: @color;
        }
        .icon-you-yuan-tianchong {
          font-size: 12px;
          color: @color;
        }
      }
    }
    .seckill-content {
      display: flex;
      justify-content: flex-start;
      align-items: center;
      .seckill-item {
        flex: 1;
        img {
          width: 100%;
        }
        .seckill-price {
          margin-top: 5px;
          text-align: center;
          color: @color;
          font-weight: bold;
        }
        .init-price {
          text-decoration: line-through;
          text-align: center;
          font-size: 12px;
          color: #ccc;
        }
      }
    }
  }

  .dong-jia-xiao-yuan {
    display: flex;
    justify-content: center;
    align-items: center;
    background-color: #f5f5f5;
    height: 35px;
    img {
      width: 184px;
    }
  }

  .category-container {
    .category-container-top {
      display: flex;
      align-items: center;
      justify-content: flex-start;
      .category-container-top-item {
        flex: 1;
        padding-top: 8px;
        box-sizing: border-box;
        &:first-child {
          border-right: 1px solid #f5f5f5;
        }
        border-bottom: 1px solid #f5f5f5;

        .item-title {
          text-align: center;
          font-size: 18px;
          height: 24px;
          line-height: 24px;
        }
        .item-text {
          text-align: center;
          font-size: 13px;
          color: #648eff;
        }
        .item-img-container {
          display: flex;
          justify-content: flex-start;
          align-items: center;
          .item-img {
            flex: 1;
            padding: 10px;
            img {
              width: 100%;
            }
          }
        }
      }
    }
    .category-container-bottom {
      display: flex;
      justify-content: flex-start;
      align-items: center;
      .category-container-bottom-item {
        flex: 1;
        padding-top: 5px;
        border-right: 1px solid #f5f5f5;
        box-sizing: border-box;
        &:last-child {
          border-right: 0;
        }
        .div-img {
          padding: 12px;
          img {
            width: 100%;
          }
        }
        .item-title {
          text-align: center;
          font-size: 15px;
          height: 24px;
          line-height: 24px;
        }
        .item-text {
          text-align: center;
          font-size: 12px;
          color: #648eff;
        }
      }
    }
  }

  .mei-ri-guang {
    background-color: #f5f5f5;
    img {
      width: 100%;
    }
  }
}
</style>
