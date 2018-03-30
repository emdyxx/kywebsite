<template>
  <div class="index">
    <!-- 导航栏 -->
    <header>
      <nav class="navbar navbar-default center">
        <div class="container-fluid"> 
        <div class="navbar-header">
          <button type="button" class="navbar-toggle" data-toggle="collapse"
              data-target="#example-navbar-collapse">
            <span class="sr-only">切换导航</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
          <a class="navbar-brand" href="/">快越网络科技有限公司</a>
        </div>
        <div class="collapse navbar-collapse" id="example-navbar-collapse">
          <ul class="nav navbar-nav navbar-right">
            <li><a href="#">公司简介</a></li>
            <li><a href="#">工业物联产品</a></li>
            <li><a href="#">服务支持</a></li>
            <li><a href="#">关于我们</a></li>
          </ul>
        </div>
        </div>
      </nav>
    </header>
    <!-- 头部大图片 -->
    <section class="imgBJ">
      <div class="bannerInnerBox">
        <div class="bannerInner">
          <h2 class="bannerInnerH2">快越科技 工业物联产品领导者</h2>
          <div class="bannerInnerText clearfix">
            <div class="redBlank"></div>
            <p>数字经济浪潮席卷全球，企业需要对其所在行业数字化转型的需求洞察与实践能力兼具的助推者。快越科技洞察数字经济发展趋势，提供满足其核心需求的产品与解决方案，加速企业数字化转型。</p>
            <a href="#" style="text-decoration: none;">
              <div class="bannerInnerBtn bannerInnerBtnPc">
                了解快越
              </div>
            </a>
          </div>
        </div>
      </div>
      <img class="imgBJ_img" :src=imgBJ_img>
    </section>
    <!-- 公司简介 -->
    <section class="firmsynopsis"> 
      <div class="containerInnerBox center">
        <h3>
          公司简介
          <!-- <div class="lookAll">查看更多</div> -->
        </h3>
        <div class="hotActivityLine">
          <div class="hotActivityImgBox">
            <img src="../assets/tendencyImg_1.jpg" alt="">
          </div>
          <div class="hotActivityBottom">
            <p>杭州快越科技有限公司是由留美博士，智能通信专家顾永海先生领衔的团队创立于2014年3月，
              坐落于浙江省杭州市滨江高新开发区，是一家为用户构建可靠安全的跨媒介端到端专网解决方案的创新企业。
              公司荣获杭州高新区5050计划2014年第一批创业发展基金；荣获2015年杭州市“雏鹰企业”。源于顾博士20多年来在国际知名
              通信企业的工作经验和在智能工厂网络方面具有的丰富的成功经验，公司的跨媒介智能专网解决方案(TSB），通过自有专利技术，
              可利用客户已有的任何一种有线/无线媒介，实现可靠安全的数据传输，提高工业车辆、数控机床、农业机械、视频监控等工业自动化、
              智能化设备等联网的可靠性、安全性和运维效率。可应用于各种智慧工业领域，特别是在无线工厂应用方面，针对工厂车间恶劣的环境，
              如波动较大的温度湿度和电磁干扰等，可以有效保障从生产设备到数据中心的可靠安全的数据传输。
            </p>
            <p>
              目前，公司提供包括有线/无线专网终端，无线基站，专网网关，网管平台在内的整体网络系统及相关产品，并可根据客户工业物联网（IIoT）
              实现的具体要求提供从数据采集、传输到格式化存储、交互服务的一揽子交钥匙工程实现。此外，快越科技还可以为有特定需求的客户提供OEM以及定制产品的开发。
            </p>
          </div>
        </div>
      </div>
    </section>
    <!-- 工业物联产品 -->
    <section class="container">
      <div class="containerInnerBox center">
        <h3 style="margin-left: 0;">
          工业物联产品
          <!-- <div class="lookAll">查看更多</div> -->
        </h3>
        <div class="containerLine">
          <div class="beAnimate">
            <div class="hotActivityInner">
              <div class="containerLineImgBox">
                <img src="../assets/20180227_3394336_0001_1067262_30008_0.jpg" alt="">
              </div>
              <div class="containerLineBottom">
                <p class="hotP">紫光旗下新华三集团主办，成都市政府和四川省经信委支持的2018 Navigate 领航者峰会，将于3月30日-31日在成都举行。</p>
                <span class="hotA">
                  关注领航者峰会
                </span>
              </div>
            </div>
            <div class="hotActivityInner">
              <div class="containerLineImgBox">
                <img src="../assets/20180227_3394336_0001_1067262_30008_0.jpg" alt="">
              </div>
              <div class="containerLineBottom">
                <p class="hotP">紫光旗下新华三集团主办，成都市政府和四川省经信委支持的2018 Navigate 领航者峰会，将于3月30日-31日在成都举行。</p>
                <span class="hotA">
                  关注领航者峰会
                </span>
              </div>
            </div>
            <div class="hotActivityInner">
              <div class="containerLineImgBox">
                <img src="../assets/20180227_3394336_0001_1067262_30008_0.jpg" alt="">
              </div>
              <div class="containerLineBottom">
                <p class="hotP">紫光旗下新华三集团主办，成都市政府和四川省经信委支持的2018 Navigate 领航者峰会，将于3月30日-31日在成都举行。</p>
                <span class="hotA">
                  关注领航者峰会
                </span>
              </div>
            </div>
            <div class="hotActivityInner">
              <div class="containerLineImgBox">
                <img src="../assets/20180227_3394336_0001_1067262_30008_0.jpg" alt="">
              </div>
              <div class="containerLineBottom">
                <p class="hotP">紫光旗下新华三集团主办，成都市政府和四川省经信委支持的2018 Navigate 领航者峰会，将于3月30日-31日在成都举行。</p>
                <span class="hotA">
                  关注领航者峰会
                </span>
              </div>
            </div>
            <div class="hotActivityInner">
              <div class="containerLineImgBox">
                <img src="../assets/20180227_3394336_0001_1067262_30008_0.jpg" alt="">
              </div>
              <div class="containerLineBottom">
                <p class="hotP">紫光旗下新华三集团主办，成都市政府和四川省经信委支持的2018 Navigate 领航者峰会，将于3月30日-31日在成都举行。</p>
                <span class="hotA">
                  关注领航者峰会
                </span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <!-- 新闻资讯 -->
    <section class="container">
      <div class="containerInnerBox center">
        <h3 style="margin-left: 0;">
          新闻资讯
          <!-- <div class="lookAll">查看更多</div> -->
        </h3>
        <div class="containerLine">
          <div class="beAnimate">
            <div class="hotActivityInner">
              <div class="containerLineImgBox">
                <img src="../assets/20180227_3394336_0001_1067262_30008_0.jpg" alt="">
              </div>
              <div class="containerLineBottom">
                <p class="hotP">紫光旗下新华三集团主办，成都市政府和四川省经信委支持的2018 Navigate 领航者峰会，将于3月30日-31日在成都举行。</p>
                <span class="hotA">
                  关注领航者峰会
                </span>
              </div>
            </div>
            <div class="hotActivityInner">
              <div class="containerLineImgBox">
                <img src="../assets/20180227_3394336_0001_1067262_30008_0.jpg" alt="">
              </div>
              <div class="containerLineBottom">
                <p class="hotP">紫光旗下新华三集团主办，成都市政府和四川省经信委支持的2018 Navigate 领航者峰会，将于3月30日-31日在成都举行。</p>
                <span class="hotA">
                  关注领航者峰会
                </span>
              </div>
            </div>
            <div class="hotActivityInner">
              <div class="containerLineImgBox">
                <img src="../assets/20180227_3394336_0001_1067262_30008_0.jpg" alt="">
              </div>
              <div class="containerLineBottom">
                <p class="hotP">紫光旗下新华三集团主办，成都市政府和四川省经信委支持的2018 Navigate 领航者峰会，将于3月30日-31日在成都举行。</p>
                <span class="hotA">
                  关注领航者峰会
                </span>
              </div>
            </div>
            <div class="hotActivityInner">
              <div class="containerLineImgBox">
                <img src="../assets/20180227_3394336_0001_1067262_30008_0.jpg" alt="">
              </div>
              <div class="containerLineBottom">
                <p class="hotP">紫光旗下新华三集团主办，成都市政府和四川省经信委支持的2018 Navigate 领航者峰会，将于3月30日-31日在成都举行。</p>
                <span class="hotA">
                  关注领航者峰会
                </span>
              </div>
            </div>
            <div class="hotActivityInner">
              <div class="containerLineImgBox">
                <img src="../assets/20180227_3394336_0001_1067262_30008_0.jpg" alt="">
              </div>
              <div class="containerLineBottom">
                <p class="hotP">紫光旗下新华三集团主办，成都市政府和四川省经信委支持的2018 Navigate 领航者峰会，将于3月30日-31日在成都举行。</p>
                <span class="hotA">
                  关注领航者峰会
                </span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>  
</template>

<script>
export default {
  name: 'index',
  data () {
    return {
      imgBJ_img:''
    }
  },
  mounted(){
    //页面刷新
    if($('.containerLine').width()<767){
      $('.hotActivityInner').css('width',$('.containerLine').width())
    }else{
      $('.hotActivityInner').css('width',$('.containerLine').width()/3-14)
    }
  },
  methods:{
    //监测是pc还是手机登录网站
    browserRedirect() {
      var sUserAgent = navigator.userAgent.toLowerCase();
      // var bIsIpad = sUserAgent.match(/ipad/i) == "ipad";
      var bIsIphoneOs = sUserAgent.match(/iphone os/i) == "iphone os";
      var bIsMidp = sUserAgent.match(/midp/i) == "midp";
      var bIsUc7 = sUserAgent.match(/rv:1.2.3.4/i) == "rv:1.2.3.4";
      var bIsUc = sUserAgent.match(/ucweb/i) == "ucweb";
      var bIsAndroid = sUserAgent.match(/android/i) == "android";
      var bIsCE = sUserAgent.match(/windows ce/i) == "windows ce";
      var bIsWM = sUserAgent.match(/windows mobile/i) == "windows mobile";
      if ( bIsIphoneOs || bIsMidp || bIsUc7 || bIsUc || bIsAndroid || bIsCE || bIsWM) {
        // 手机端
        this.imgBJ_img = '/static/indexBannerMbl.jpg'
        $('.hotActivityInner').css('width',$('.containerLine').width())
      } else {
        // pc端
        this.imgBJ_img = '/static/banner_1.jpg'
        $('.hotActivityInner').css('width',$('.containerLine').width()/3-14)
      }
    }
  },
  created(){
    var that = this
    this.browserRedirect();
    $(window).resize(function () {//当浏览器大小变化时
      if($(document.body).width()>550){
        that.imgBJ_img = '/static/banner_1.jpg'
      }else{
        that.imgBJ_img = '/static/indexBannerMbl.jpg'
      }
      if($('.containerLine').width()<767){
        $('.hotActivityInner').css('width',$('.containerLine').width())
      }else{
        $('.hotActivityInner').css('width',$('.containerLine').width()/3-14)
      }
    });
  }
}
</script>
<style scoped>
.index{width: 100%;height: 100%;}
/* 宽度大于1280px 电脑端*/
@media (min-width: 1280px) {
  .navbar-brand{font-size: 26px;}
  .center{width: 1280px;margin: 0 auto;padding-left: 10px;padding-right: 10px;}
  nav{font-size: 18px;}
  .bannerInnerH2{font-size: 50px;margin: 50px 0 27px;}
  .bannerInnerText{font-size: 16px;}
  .bannerInnerBtn{width: 150px;height: 40px;line-height: 40px;font-size:16px;margin-top:28px;}
  .containerInnerBox>h3{font-size: 30px;margin-top:20px;margin-bottom:15px;}
  .hotActivityLine{flex-wrap: nowrap;}
  .hotActivityImgBox{width:282px;}
  .hotActivityImgBox>img{width:282px;}
  .hotActivityBottom{width: 996px;padding-left: 20px;}
}
/* 宽度767-1280px  平板端*/
@media (min-width:767px) and (max-width: 1280px) {
  .navbar-brand{font-size: 22px;}
  .center{width: 100%;}
  .navbar-right{background: none;}
  nav{font-size: 16px;}
  .bannerInnerH2{font-size: 35px;margin: 30px 0 27px;}
  .bannerInnerText{font-size: 14px;}
  .bannerInnerBtn{width: 130px;height: 30px;line-height: 30px;font-size:14px;margin-top:22px;}
  .containerInnerBox>h3{font-size: 28px;margin-top:15px;margin-bottom:10px;}
  .hotActivityLine{flex-wrap: nowrap;}
  .hotActivityImgBox{width:40%;}
  .hotActivityImgBox>img{width:100%;}
  .hotActivityBottom{width: 60%;padding-left: 20px;}
}
/* 宽度767以下  手机端 */
@media (max-width: 767px){
  .navbar-brand{font-size: 18px;}
  .navbar-right{background: #e7e7e7;}
  nav{font-size: 14px;}
  .bannerInnerH2{font-size: 18px;margin: 10px 0 27px;}
  .bannerInnerText{font-size: 13px;}
  .bannerInnerBtn{width: 110px;height: 30px;line-height: 30px;font-size:16px;margin-top:16px;}
  .containerInnerBox>h3{font-size: 19px;margin-top:10px;margin-bottom:5px;}
  .hotActivityLine{flex-wrap: wrap;}
  .hotActivityImgBox{width:100%;}
  .hotActivityImgBox>img{width:100%;}
}

header{position: fixed;top: 0;width: 100%;height: 80px;background: white;box-shadow: 0px 1px 1px rgba(0,0,0,0.1);z-index: 9999;}
header>nav{background: white;border: none;height: 80px;margin: 0 auto;}
header>nav>div{margin-top:15px;}
.navbar-brand{color: #01060ecc;}
.navbar-nav>li>a{color: #000000b3;}
.imgBJ{width: 100%;margin-top: 80px;position: relative;}
.imgBJ>img{width: 100%;}
.bannerInnerBox{width: 100%;height: 100%;position: absolute;top: 0;left: 0;z-index: 10;}
.bannerInner{width: 100%;height: auto;max-width: 1232px;min-width: 320px;padding: 0 10px;margin: 0 auto;text-align: left;}
.bannerInnerH2{color: #fff;font-weight: 400;text-shadow: 0 5px 5px rgba(0,0,0,0.2);line-height: 1;}
.bannerInnerText{width: 100%;position: relative;max-width: 585px;color: white;padding-left: 15px;padding-top:2px;}
.redBlank{width: 4px;height: 98%;background: #e60012;position: absolute;top: 5px;left: 0;}
.bannerInnerText>a{width: auto;}
.bannerInnerBtn{color:white;cursor: pointer;background: red;border-radius: 40px;text-align: center;}
.firmsynopsis,.container{width: 100%;}
.containerInnerBox>h3{text-align: left;padding-left: 10px;border-left: 5px solid #e60012;margin-left: 10px;}
/* .lookAll{font-size: 14px;line-height: 34px;float: right;vertical-align: middle;cursor: pointer;} */
.hotActivityLine{display:flex;box-shadow: 0px 3px 8px rgba(0,0,0,0.1);padding:15px 15px;margin: 5px;}
.hotActivityBottom{max-height: 204px;overflow: hidden;}
.hotActivityBottom>p{width:100%;text-align: left;font-size: 14px;color: #666;line-height: 24px;}
.containerLine{position: relative;width: 100%;overflow: hidden;}
.beAnimate{overflow: hidden;width: 4000px;padding-bottom: 10px;}
.hotActivityInner{background: white;margin-right: 20px;float: left;box-shadow: 0px 3px 8px rgba(0,0,0,0.1);cursor: pointer;}
.containerLineImgBox{width: 100%;height: auto;position: relative;overflow: hidden;}
.containerLineImgBox>img{width: 100%;transition: all 1s;-webkit-transition: all 0.5s;}
.containerLineBottom{position: relative;margin-top: 10px;margin-bottom: 35px;}
.hotP{font-size: 14px;padding: 0 14px;text-align: left;color: #666;}
.hotA{font-size: 14px;position: absolute;line-height: 1;display: block;right: 22px;}
.hotActivityInner:hover>.containerLineImgBox>img{transform: scale(1.2);-webkit-transform: scale(1.2)}
.hotActivityInner:hover>.containerLineBottom>.hotA{color: red;}
</style>
