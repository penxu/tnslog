<template>
  <div class="home-container">
    <Carousel />
    <div class="service-item-container container">
        <h1 class="fancy-heading themify-text-center">
        <span class="main-head"><b>我们的服务</b></span>
        <br>
        <span class="sub-head">我们是卓越物流公司，服务于在国际航运，陆上运输，海关经纪和交付等方面的服务</span>
        </h1>
    </div>
    <div class="container service-item" style="padding-top: 30px;">
      <div class="row">
        <div class="col-sm">
          <div class="icon-item-box">
            <div class="icon-item"><i class="iconfont icon-sea-port icon-service"></i></div>
            <div class="icon-des">海上运输</div>
          </div>
          
        </div>
        <div class="col-sm">
          <div class="icon-item-box">
            <div class="icon-item"><i class="iconfont icon-fly icon-service"></i></div>
            <div class="icon-des">空中运输</div>
          </div>
        </div>
        <div class="col-sm">
          <div class="icon-item-box">
            <div class="icon-item"><i class="iconfont icon-truck icon-service"></i></div>
            <div class="icon-des">陆地运输</div>
          </div>
        </div>
      </div>
      <div class="row"  style="padding-top: 30px;">
        <div class="col-sm">
          <div class="icon-item-box">
            <div class="icon-item"><i class="iconfont icon-town-bus icon-service"></i></div>
            <div class="icon-des">报关</div>
          </div>
          
        </div>
        <div class="col-sm">
          <div class="icon-item-box">
            <div class="icon-item"><i class="iconfont icon-cargo icon-service"></i></div>
            <div class="icon-des">仓库 </div>
          </div>
        </div>
        <div class="col-sm">
          <div class="icon-item-box">
            <div class="icon-item"><i class="iconfont icon-box icon-service"></i></div>
            <div class="icon-des">装箱/拆箱</div>
          </div>
        </div>
      </div>
    </div>

    <div class="cooperative_partner index-header">
            <p class="header">
            <span>合作伙伴</span></p>
            <div class="newsStyle">
                <span>cooperative partner</span>
            </div>
      <div class="row parnar-img-box">
        <div class="col-4 col-md-2 parnar-img" v-for=" (img, index) of imgList" :key="index"><img :src="img.img" alt=""></div>
      </div>
    </div>

  </div>
</template>

<script>
// @ is an alias to /src

import Carousel from '@/components/Carousel.vue'
export default {
  name: 'Home',
  components: {
    Carousel
  },
  data () {
    return {
      imgList: [
        {img: require('../assets/parnar-img/link_20.jpg')},
        {img: require('../assets/parnar-img/link_21.jpg')},
        {img: require('../assets/parnar-img/link_23.jpg')},
        {img: require('../assets/parnar-img/link_24.jpg')},
        {img: require('../assets/parnar-img/link_25.jpg')},
        {img: require('../assets/parnar-img/link_26.jpg')},
        {img: require('../assets/parnar-img/link_27.jpg')},
        {img: require('../assets/parnar-img/link_28.jpg')},
        {img: require('../assets/parnar-img/link_29.jpg')},
        {img: require('../assets/parnar-img/link_30.jpg')},
        {img: require('../assets/parnar-img/link_31.jpg')},
        {img: require('../assets/parnar-img/link_32.jpg')},
        {img: require('../assets/parnar-img/link_33.jpg')},
        {img: require('../assets/parnar-img/link_38.jpg')},
        {img: require('../assets/parnar-img/link_39.jpg')},
        {img: require('../assets/parnar-img/link_40.jpg')},
        {img: require('../assets/parnar-img/link_41.jpg')},
        {img: require('../assets/parnar-img/link_44.jpg')},
        {img: require('../assets/parnar-img/link_45.jpg')},
        {img: require('../assets/parnar-img/link_46.jpg')},
      ]
    }
  },
  methods: {

  },
      mounted() {
      console.log(this.imgList, 'headers')
      console.log('headers')
    }
}
</script>

<style lang="scss" scoped>
  .home-container {
    padding: 50px 0 0 0;
  }
  .service-item-container {
    padding-top: 30px;
    .main-head {
      b {
        font-size: 36px;
        border-bottom: 1px solid #1890FF;
        &::before {
          content: "";
          display: inline-block;
          width: 100px;
          background: #2787fa;
          height: 4px;
          margin: 0px -102px -18px 0px;
          }
      }
    }
  }
  .service-item {
    .icon-item-box {
      text-align: center;
      .icon-item {
        text-align: center;
        margin: 0 auto;
        width: 62px;
        height: 62px;
        border-radius: 50%;
        background: #dd3333;
      }
      .icon-service {
        font-size: 40px;
        color: #fff;
      }
    }
    .icon-des {
      padding-top: 10px;
      font-size: 18px;
      color: #666666;
    }
  }
    .index-header {
      padding-top:  50px ;
      color: #666;
      margin: 0;
      text-align: center;
      .header {
        margin-bottom: 0;
        span {
          border-bottom: 1px solid #1890FF;
          font-size: 36px;
          color: #17171A;
          line-height: 50px;
          height: 50px;
          display: inline-block;
        }
      }
      .newsStyle {
        span {
          margin: 0 0 0 -19px;
          padding: 0;
          display: inline-block;
          height: 34px;
          line-height: 34px;
          // font-size: 1.2rem;
          color: #666;
          &::before {
            content: "";
            display: inline-block;
            width: 68px;
            background: #2787fa;
            height: 4px;
            float: left;
            margin: 0px -68px 0 0px;
          }
        }
      }
      .parnar-img-box {
        padding: 15px 200px 0 200px;
        margin:0;
        .parnar-img {
          margin-bottom: 40px;
        }
      }
    }
</style>

