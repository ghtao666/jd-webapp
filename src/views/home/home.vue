<template>
  <div class="home">
    <tgh-header></tgh-header>

    <!-- 轮播图 -->
    <div class="swipe-container">
      <van-swipe :autoplay="3000" indicator-color="white">
        <van-swipe-item>
          <img
            src="//m.360buyimg.com/mobilecms/s750x366_jfs/t1/17486/31/4181/99175/5c2f465fEbe754e16/cd1c5695ee715610.jpg!cr_1125x549_0_72!q70.jpg.dpg"
            alt
          >
        </van-swipe-item>
        <van-swipe-item>
          <img
            src="//m.360buyimg.com/mobilecms/s750x366_jfs/t1/23360/8/4031/468576/5c2dc861E189161bc/bac4293f6060aa5f.jpg!cr_1125x549_0_72!q70.jpg.dpg"
            alt
          >
        </van-swipe-item>

        <van-swipe-item>
          <img
            src="//m.360buyimg.com/mobilecms/s750x366_jfs/t1/17595/2/3960/100854/5c2c792fE5479c25a/23c861d84eb642de.jpg!cr_1125x549_0_72!q70.jpg.dpg"
            alt
          >
        </van-swipe-item>

        <van-swipe-item>
          <img
            src="//m.360buyimg.com/mobilecms/s750x366_jfs/t23554/196/252614617/149239/73b66270/5b2a6ecdNc10d686b.jpg!cr_1125x549_0_72!q70.jpg.dpg"
            alt
          >
        </van-swipe-item>
      </van-swipe>
    </div>

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
          <span class="seckill-time">22点场</span>
          <count-down></count-down>
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
            src="//img14.360buyimg.com/n1/s150x150_jfs/t1/8987/5/10181/94637/5c208bd8Eae90304a/b7d847b6a42be460.jpg.dpg"
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
            src="//img14.360buyimg.com/n1/s150x150_jfs/t1/27784/2/4208/151514/5c2f20adEd10158d7/d30cf3ceaa6795db.jpg.dpg"
            alt
          >
          <div class="seckill-price">￥4899</div>
          <div class="init-price">￥5199</div>
        </div>
      </div>
    </div>

    <div class="new-people-gif">
      <img
        src="//m.360buyimg.com/mobilecms/jfs/t1/19774/32/3402/157493/5c2709cfE99b0d1ef/f2ea3a8cb134cfc4.gif"
        alt
      >
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
          <div class="item-title">— 奢品大牌 —</div>
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
          <div class="item-title">— 秋冬童装 —</div>
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

    <div class="category-container">
      <div class="category-container-bottom">
        <div class="category-container-bottom-item">
          <div class="item-title gradual-1">拍拍二手</div>
          <div class="item-text text-black">iPhone 5折起</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/mobilecms/s150x150_jfs/t14251/339/1738489148/26244/792efe55/5a56fd12N458f4fe7.jpg!q70.jpg.dpg"
            >
          </div>
        </div>

        <div class="category-container-bottom-item">
          <div class="item-title gradual-2">品牌秒杀</div>
          <div class="item-text text-black">低价抢大牌</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/mobilecms/s150x150_jfs/t17464/360/397374747/63054/a11b2fb/5a72e34cNf6da61e6.png!q70.jpg.dpg"
            >
          </div>
        </div>

        <div class="category-container-bottom-item">
          <div class="item-title gradual-1">闪购</div>
          <div class="item-text text-black">精选1元购</div>
          <div class="div-img">
            <img
              src="//img14.360buyimg.com/n1/s150x150_jfs/t1/21691/8/3972/197770/5c2dc23dEb39ab4e5/42297e0199e10b53.jpg.dpg"
            >
          </div>
        </div>

        <div class="category-container-bottom-item">
          <div class="item-title gradual-2">优享免息</div>
          <div class="item-text text-black">分期免息费</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/n1/s150x150_jfs/t1/18949/39/4013/149552/5c2d6afcE26a553a3/9ce02c746f96c85d.jpg!q70.jpg.dpg"
            >
          </div>
        </div>
      </div>
    </div>

    <!-- 分割线---爱生活 -->
    <div class="mei-ri-guang">
      <img
        src="//m.360buyimg.com/mobilecms/s750x80_jfs/t15526/56/2344102455/23273/d8e15d5a/5aa0dbc1Nefd2bd2a.png!q70.jpg.dpg"
      >
    </div>

    <div class="category-container">
      <div class="category-container-top">
        <div class="category-container-top-item love-live">
          <div class="item-title love-live-title">玩3C</div>
          <div class="item-text love-live-text">玩转3C科技</div>
          <div class="item-img-container">
            <div class="item-img">
              <img
                src="//m.360buyimg.com/n1/s150x150_jfs/t25144/2/1278469398/101844/cb66b21/5b90f5bfNcd58f18b.png!q70.jpg.dpg"
                alt
              >
            </div>

            <div class="item-img">
              <img
                src="//m.360buyimg.com/mobilecms/s150x150_jfs/t22792/274/2587775944/59292/3666f607/5b87bf15N9409ba0e.png!q70.jpg.dpg"
                alt
              >
            </div>
          </div>
        </div>
        <div class="category-container-top-item love-live">
          <div class="item-title love-live-title">京东家电</div>
          <div class="item-text love-live-text">家电狂欢 京彩有你</div>
          <div class="item-img-container">
            <div class="item-img">
              <img
                src="//m.360buyimg.com/mobilecms/s150x150_jfs/t22363/318/1484948466/11138/8317fc9b/5b2a528eN7c6bde83.jpg!q70.jpg.dpg"
                alt
              >
            </div>

            <div class="item-img">
              <img
                src="//m.360buyimg.com/mobilecms/s150x150_jfs/t22666/293/257815171/29274/6b5605b1/5b2a5295N5a81ad96.jpg!q70.jpg.dpg"
                alt
              >
            </div>
          </div>
        </div>
      </div>
      <div class="category-container-top">
        <div class="category-container-top-item love-live">
          <div class="item-title love-live-title">京东超市</div>
          <div class="item-text love-live-text">超市大放价 抢超值好货</div>
          <div class="item-img-container">
            <div class="item-img">
              <img
                src="//m.360buyimg.com/n1/s150x150_jfs/t16852/170/2693122660/56143/28da8c2a/5b063c63N5746e4e4.jpg!q70.jpg.dpg"
                alt
              >
            </div>

            <div class="item-img">
              <img
                src="//m.360buyimg.com/n1/s150x150_jfs/t18877/293/2631103430/85245/f220b40d/5b063c6fN7820b399.jpg!q70.jpg.dpg"
                alt
              >
            </div>
          </div>
        </div>
        <div class="category-container-top-item love-live">
          <div class="item-title love-live-title">爱家</div>
          <div class="item-text love-live-text">家纺热卖 部分低至9.9元</div>
          <div class="item-img-container">
            <div class="item-img">
              <img
                src="//m.360buyimg.com/mobilecms/s150x150_jfs/t15244/283/356547262/47743/b6607b0f/5a2a6d51N8830e8b8.jpg!q70.jpg.dpg"
                alt
              >
            </div>

            <div class="item-img">
              <img
                src="//m.360buyimg.com/mobilecms/s150x150_jfs/t16057/38/102057973/36179/b957e4ec/5a2a6d55N83655f7f.jpg!q70.jpg.dpg"
                alt
              >
            </div>
          </div>
        </div>
      </div>
      <div class="category-container-bottom">
        <div class="category-container-bottom-item love-live">
          <div class="item-title love-live-title">家有萌宝</div>
          <div class="item-text love-live-text">低至5折</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/n1/s150x150_jfs/t17929/299/899794385/17291/d90318f9/5ab4c680N7d291625.jpg!q70.jpg.dpg"
            >
          </div>
        </div>

        <div class="category-container-bottom-item love-live">
          <div class="item-title love-live-title">个护馆</div>
          <div class="item-text love-live-text">9.9元拼购</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/n1/s150x150_jfs/t1/9920/35/9955/298173/5c1c3fdaE20128253/2a69b534052fb4c9.jpg!q70.jpg.dpg"
            >
          </div>
        </div>

        <div class="category-container-bottom-item love-live">
          <div class="item-title love-live-title">爱吃</div>
          <div class="item-text love-live-text">9.9包邮</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/mobilecms/s150x150_jfs/t14473/103/2042876100/41836/766c1953/5a697f47Nc952ed7f.jpg!q70.jpg.dpg"
            >
          </div>
        </div>

        <div class="category-container-bottom-item love-live">
          <div class="item-title love-live-title">时尚衣橱</div>
          <div class="item-text love-live-text">百变女神</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/mobilecms/s150x150_jfs/t20260/181/224299388/42393/9632586f/5b053603N0f65aec5.jpg!q70.jpg.dpg"
            >
          </div>
        </div>
      </div>
    </div>

    <!-- 分割线---逛商场 -->
    <div class="mei-ri-guang">
      <img
        src="//m.360buyimg.com/mobilecms/s750x80_jfs/t19381/275/717008577/26686/e58b7ef4/5aa23f27Nfa6d6be3.png!q70.jpg.dpg"
      >
    </div>

    <div class="category-container">
      <div class="category-container-top-guang-shang-chang">
        <div class="guang-shang-chang-item">
          <div class="guang-shang-chang-item-left">
            <div class="guang-shang-chang-title">医药城</div>
            <div class="guang-shang-chang-text">大牌直降</div>
          </div>
          <div class="guang-shang-chang-item-right">
            <img
              src="//m.360buyimg.com/n1/s180x180_jfs/t17266/210/329403888/25547/5451c4a5/5a6aece8Nbd3e4c89.jpg!q70.jpg.dpg"
            >
          </div>
        </div>
        <div class="guang-shang-chang-item">
          <div class="guang-shang-chang-item-left">
            <div class="guang-shang-chang-title">进口馆</div>
            <div class="guang-shang-chang-text">满199减100</div>
          </div>
          <div class="guang-shang-chang-item-right">
            <img
              src="//m.360buyimg.com/n1/s180x180_jfs/t15823/197/1830681024/449185/d32f9121/5a6955a1N1a5353c0.jpg!q70.jpg.dpg"
            >
          </div>
        </div>
      </div>
      <div class="category-container-top-guang-shang-chang">
        <div class="guang-shang-chang-item">
          <div class="guang-shang-chang-item-left">
            <div class="guang-shang-chang-title">内衣馆</div>
            <div class="guang-shang-chang-text">年中狂欢购</div>
          </div>
          <div class="guang-shang-chang-item-right">
            <img
              src="//m.360buyimg.com/n1/s180x180_jfs/t20995/242/758982428/30159/affb6143/5b1795cbN1b3b96b1.jpg!q70.jpg.dpg"
            >
          </div>
        </div>
        <div class="guang-shang-chang-item">
          <div class="guang-shang-chang-item-left">
            <div class="guang-shang-chang-title">美妆馆</div>
            <div class="guang-shang-chang-text">免费试用</div>
          </div>
          <div class="guang-shang-chang-item-right">
            <img
              src="//m.360buyimg.com/n1/s180x180_jfs/t1/11094/6/2903/395639/5c18d4baE538da852/3d6cd9b6efe72599.jpg!q70.jpg.dpg"
            >
          </div>
        </div>
      </div>
      <div class="category-container-bottom guang-shang-chang">
        <div class="category-container-bottom-item guang-shang-chang">
          <div class="item-title guang-shang-chang-title">美食城</div>
          <div class="item-text guang-shang-chang-text">低至5折</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/mobilecms/s150x150_jfs/t16705/82/285076461/40568/d2f7fc14/5a698c01Nab864629.jpg!q70.jpg.dpg"
            >
          </div>
        </div>

        <div class="category-container-bottom-item guang-shang-chang">
          <div class="item-title guang-shang-chang-title">手机馆</div>
          <div class="item-text guang-shang-chang-text">享白条免息</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/n1/s150x150_jfs/t1/1314/33/11714/171227/5bd01017E066acc3f/381f3dd2118227ec.jpg!q70.jpg.dpg"
            >
          </div>
        </div>

        <div class="category-container-bottom-item guang-shang-chang">
          <div class="item-title guang-shang-chang-title">生鲜馆</div>
          <div class="item-text guang-shang-chang-text">尝鲜秒杀</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/n1/s150x150_jfs/t24940/151/2670283760/320387/8d571f7b/5bece337Na6d4e8c5.jpg!q70.jpg.dpg"
            >
          </div>
        </div>

        <div class="category-container-bottom-item guang-shang-chang">
          <div class="item-title guang-shang-chang-title">家装城</div>
          <div class="item-text guang-shang-chang-text">家装一站购</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/n1/s150x150_jfs/t21118/317/454557829/72252/b89aac99/5b0e6ad9N67c11d54.jpg!q70.jpg.dpg"
            >
          </div>
        </div>
      </div>
      <div class="category-container-bottom">
        <div class="category-container-bottom-item guang-shang-chang">
          <div class="item-title guang-shang-chang-title">钟表馆</div>
          <div class="item-text guang-shang-chang-text">百元直降</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/n1/s150x150_jfs/t16618/154/356149823/20882/5e1d0792/5a6e8cb8N2873f417.jpg!q70.jpg.dpg"
            >
          </div>
        </div>

        <div class="category-container-bottom-item guang-shang-chang">
          <div class="item-title guang-shang-chang-title">童装馆</div>
          <div class="item-text guang-shang-chang-text">爱尚童潮</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/n1/s150x150_jfs/t20614/194/808562651/89118/894d41a5/5b18ba8dN855ebe44.png!q70.jpg.dpg"
            >
          </div>
        </div>

        <div class="category-container-bottom-item guang-shang-chang">
          <div class="item-title guang-shang-chang-title">奢品馆</div>
          <div class="item-text guang-shang-chang-text">奢品精选</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/n1/s150x150_jfs/t19339/53/365151960/30948/61e1b312/5a6e8c33Ne82f49d9.jpg!q70.jpg.dpg"
            >
          </div>
        </div>

        <div class="category-container-bottom-item guang-shang-chang">
          <div class="item-title guang-shang-chang-title">珠宝馆</div>
          <div class="item-text guang-shang-chang-text">满减优惠</div>
          <div class="div-img">
            <img
              src="//m.360buyimg.com/n1/s150x150_jfs/t19009/357/347377157/13661/d0d9e5fb/5a6e8bb3Nd6182f9f.jpg!q70.jpg.dpg"
            >
          </div>
        </div>
      </div>
    </div>

    <div class="divider-recommend">
      <span>————</span>
      <span class="recommend-text">为你推荐</span>
      <span>————</span>
    </div>
    <tgh-tabbar></tgh-tabbar>
  </div>
</template>


<script>
import TghHeader from "@/components/tgh-header";
import TghTabbar from "@/components/tgh-tabbar";
import CountDown from "@/components/count-down";
export default {
  data() {
    return {};
  },
  components: {
    TghHeader,
    TghTabbar,
    CountDown
  }
};
</script>


<style lang="less" >
@color: #e83632;
.home {
  padding-bottom: 100px;
  .swipe-container {
    .van-swipe {
      height: 182px;
      img {
        width: 100%;
      }
      .van-swipe__indicators {
        bottom: 20px;
        .van-swipe__indicator {
          // background-color: transparent;
          // border:1px solid #fff;
          // box-sizing: border-box;
          // width: 6px;
          // height: 6px;
        }
      }
    }
  }

  .nav-container {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    flex-wrap: wrap;
    background-color: #fff;
    border-top-left-radius: 15px;
    border-top-right-radius: 15px;
    transform: translateY(-13px);
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
    justify-content: flex-start;
    margin-top: 5px;
    img {
      width: 73px;
      margin-left: 10px;
      margin-right: 10px;
    }
    .van-swipe {
      flex: 1;
      height: 20px;
      line-height: 20px;
      .van-swipe-item {
        height: 20px;
        line-height: 20px;
        display: flex;
        justify-content: center;
        align-items: center;
      }
      .hot {
        color: @color;
        font-size: 14px;
        margin-right: 5px;
      }
      .content {
        display: inline-block;
        overflow: hidden;
        text-overflow: ellipsis;
        white-space: nowrap;
        font-size: 14px;
      }
    }
    span.more {
      margin-right: 10px;
      margin-left: 5px;
      color: #181818;
      font-size: 14px;
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
    .seckill-top {
      display: flex;
      justify-content: space-between;
      align-items: center;
      height: 20px;
      .seckill-top-left {
        display: flex;
        align-items: center;
        .seckill-text {
          color: @color;
          font-weight: bold;
          font-size: 18px;
        }
        .seckill-time {
          font-size: 12px;
          font-weight: bold;
          margin-left: 5px;
        }
      }

      .seckill-top-right {
        display: flex;
        align-items: center;
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
          font-size: 16px;
        }
        .init-price {
          text-decoration: line-through;
          text-align: center;
          font-size: 12px;
          color: #ccc;
          font-size: 12px;
        }
      }
    }
  }
  .new-people-gif {
    img {
      width: 100%;
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
        &.love-live {
          padding-left: 10px;
          padding-right: 10px;
        }

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
        .love-live-title {
          text-align: left;
          font-size: 16px;
        }

        .item-text {
          text-align: center;
          font-size: 12px;
          color: #648eff;
        }
        .love-live-text {
          text-align: left;
          color: @color;
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
      &.guang-shang-chang {
        border-bottom: 1px solid #f5f5f5;
      }
      .category-container-bottom-item {
        flex: 1;
        padding-top: 5px;
        border-right: 1px solid #f5f5f5;
        box-sizing: border-box;
        &.love-live {
          padding-left: 10px;
          padding-right: 10px;
        }
        &.guang-shang-chang {
          padding-left: 10px;
          padding-right: 10px;
        }
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
        .love-live-title {
          text-align: left;
          font-size: 16px;
        }
        .guang-shang-chang-title {
          text-align: left;
          font-size: 16px;
        }
        .gradual-1 {
          background: linear-gradient(90deg, #ff2a2a, #f139d2);
          color: transparent;
          background-clip: text;
          -webkit-background-clip: text;
        }
        .gradual-2 {
          background: linear-gradient(90deg, #fe8537, #f02b2b);
          color: transparent;
          background-clip: text;
          -webkit-background-clip: text;
        }
        .item-text {
          text-align: center;
          font-size: 12px;
          color: #648eff;
        }
        .love-live-text {
          text-align: left;
          color: @color;
        }
        .guang-shang-chang-text {
          text-align: left;
          color: #d663e1;
        }
        .text-black {
          color: #222222;
        }
      }
    }
    .category-container-top-guang-shang-chang {
      display: flex;
      justify-content: flex-start;
      align-items: center;
      border-bottom: 1px solid #f5f5f5;
      .guang-shang-chang-item {
        flex: 1;
        display: flex;
        justify-content: flex-start;
        &:first-child {
          border-right: 1px solid #f5f5f5;
        }
        .guang-shang-chang-item-left {
          flex: 1;
          padding-left: 10px;
          padding-top: 10px;
          .guang-shang-chang-title {
            text-align: left;
            font-size: 16px;
          }
          .guang-shang-chang-text {
            text-align: left;
            color: #d663e1;
            font-size: 12px;
          }
        }
        .guang-shang-chang-item-right {
          flex: 1;
          img {
            width: 100%;
          }
        }
      }
    }
  }

  .mei-ri-guang {
    background-color: #f5f5f5;
    height: 35px;
    img {
      width: 100%;
    }
  }

  .divider-recommend {
    height: 35px;
    background-color: #f6f6f6;
    display: flex;
    align-items: center;
    justify-content: center;
    span {
      color: #848689;
      font-size: 14px;
    }
    .recommend-text {
      margin-left: 15px;
      margin-right: 15px;
    }
  }
}
</style>
