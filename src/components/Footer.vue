<template>
  <div class="footer-container">
    <footer class="site-footer" role="contentinfo">
      <div class="footer-item-box">
        <div class="container">
          <div class="row">
            <div class="col-sm">
              <div class="footer-item">
                  <div class="footer-header">公司</div>
                  <div class="nav-li"><router-link to="/home">首页</router-link></div>
                  <div class="nav-li"><router-link to="/about">关于我们</router-link></div>
                  <div class="nav-li"><router-link to="/contact">联系我们</router-link></div>
              </div>
            </div>
            <div class="col-sm">
              <div class="footer-item">
                  <div class="footer-header">服务</div>
                
                  <div class="nav-li"><router-link to="/service">海上运输</router-link></div>
                  <div class="nav-li"><router-link to="/service">陆上运输</router-link></div>
                  <div class="nav-li"><router-link to="/service">空中运输</router-link></div>
                  <div class="nav-li"><router-link to="/service">货运代理</router-link></div>
                  <div class="nav-li"><router-link to="/service">仓储</router-link></div>
                  <div class="nav-li"><router-link to="/service">装箱/拆箱</router-link></div>

              </div>
            </div>
            <div class="col-sm">
              <div class="footer-item">
                  <div class="footer-header">联系我们</div>
                  <div class="nav-li ">
                    <div class="text">
                      <p>徐小姐(海外销售经理)</p>
                      <p>电话: (+86)755-85768909</p>
                      <p>传真:(+86)755-23579789</p>
                      <p>手机:(+86)18818998559</p>
                      <p>邮箱: lihua.xu@tnslog.com</p>
                      <p>Skype:+8613640231815</p>
                      <p>QQ: 2149952468</p>
                      <p>地址：广东省深圳市前海深港合作区前湾一路1号A栋201室</p>                   
                    </div>
                    </div>
              </div>
            </div>
            <div class="col-sm">
              <div class="footer-item">
                  <div class="footer-header">马来西亚总部</div>
                  <div class="nav-li ">
                    <div class="text">
                      <p>TNS LOG SERVICES SDN BHD (1090197-X)</p>
                      <p>TEL:852-36115584</p>
                      <p>FAX:852-36115585</p>
                      <p>EMAIL:lucy@szsdi.com, lucy@sdilogistics.com</p>
                      <p>ADD: : 28B (2nd Floor), Jalan Sentosa 5,Taman Bayu Tinggi, 41200 Klang,Selangor Darul Ehsan, Malaysia</p>
                      <p>Tel: +603 3319 0318</p>
                      <p>Email：hanson.lee@tnslog.com.my</p>
                    </div>
                    </div>
              </div>
            </div>
          </div>
      </div>
      </div>
      <div class="copyright">
            © TNS Logistic Service Sdn Bhd 2019. All Rights Reserved. Powered by penxu WebDesign
      </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'Footer',
  props: {
    
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .footer-container {
    .footer-item {
      font-size: 14px;
    }
  }
  .site-footer {
    .copyright {
      background-color: #1f1f1f;
      padding: 30px 0;
      text-align: center;
      color: #b7b7b7
    }
  }
  .footer-item-box {
    padding: 60px 0;
    background-image: url(http://tnslog.com.my/wp-content/uploads/2016/11/footer-widget-bg.jpg);
    background-size:cover;
    .footer-item {
      .footer-header {
        font-size: 18px;
        color: #fff;
        line-height: 40px;
      }
      .nav-li {
          font-size: 16px;
          color: #fff;
          opacity: .6;
        a {
          line-height: 40px;
          font-size: 16px;
          color: #fff;
          opacity: .6;
        }
      }
      .text {
        // text-align: left;
        margin-top: 7px;
      }
    }
  }

</style>
