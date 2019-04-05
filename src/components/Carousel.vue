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
        <img class="d-block w-100" src="../../public/img/banner1.jpg" alt="First slide">
            <div class="carousel-caption d-none d-md-block">
            <h2>海运服务：</h2>
            <p>海运进出口业务，国际多联式联运业务。内贸运输业务。DDP/DDU服务 </p>
          </div>
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src=" https://tnslog.com.my/wp-content/uploads/2016/05/homeslider_3-1.jpg" alt="Second slide">
            <div class="carousel-caption d-none d-md-block">
            <h2>空运服务</h2>
            <p>空运进出口，代理报关报检，仓储装卸，地面运输，货物包装及门到门的贴心服务</p>
          </div>
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="https://tnslog.com.my/wp-content/uploads/2016/05/homeslider_4-new-1.jpg" alt="Third slide">
          <div class="carousel-caption d-none d-md-block">
            <h2>陆运服务</h2>
            <p>提供集装箱，零担散货，海关监管车等运输服务</p>
          </div>
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="https://tnslog.com.my/wp-content/uploads/2016/05/homeslider_2.jpg" alt="Third slide">
                    <div class="carousel-caption d-none d-md-block">
            <h2>特殊服务：</h2>
            <p style="padding: 0 50px;">转口贸易，专业优质的一站式第三国转口贸易 ，普通化工品的进出口业务，特种集装箱（开顶柜，平板柜。框架柜等）国际运输</p>
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