<template>
  <div id="carouselExampleControls" class="carousel slide carousel-container" data-ride="carousel">
      <!-- <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
  </ol> -->
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img class="d-block w-100" src="https://tnslog.com.my/wp-content/uploads/2016/05/homeslider_1.jpg" alt="First slide">
            <div class="carousel-caption d-none d-md-block">
            <h2>马来西亚总部</h2>
            <p>立足于马来西亚和中国，放眼全球，更加专业。</p>
          </div>
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="https://tnslog.com.my/wp-content/uploads/2016/05/homeslider_2.jpg" alt="Second slide">
            <div class="carousel-caption d-none d-md-block">
            <h2>海运服务</h2>
            <p>10年经验，全世界各国都很强大的代理支持。</p>
          </div>
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="https://tnslog.com.my/wp-content/uploads/2016/05/homeslider_3-1.jpg" alt="Third slide">
                    <div class="carousel-caption d-none d-md-block">
            <h2>空运服务</h2>
            <p>你会得到快速，高效的国际空运提货全球。</p>
          </div>
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="https://tnslog.com.my/wp-content/uploads/2016/05/homeslider_4-new-1.jpg" alt="Third slide">
          <div class="carousel-caption d-none d-md-block">
            <h2>陆运服务</h2>
            <p>资源整合配置我们能够快速把货物运到出口港或者送到客户手上。</p>
          </div>
      </div>
    </div>
    <a class="carousel-control-prev" href="#carouselExampleControls" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next" href="#carouselExampleControls" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
    
  </div>
</template>

<script>
export default {
  name: 'Carousel',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .carousel-container {
    // min-height: 300px;
    .carousel-item:nth-child(2n) {
      // min-height: 300px;
      background: #ccc;
    }
    .carousel-item:nth-child(2n+1) {
      // min-height: 300px;
      background: #e7e7e7;
    }
    .carousel-caption {
        background-color:rgba(0,0,0,0.5);
        left:0;
        right: 50%;
    }
  }
</style>