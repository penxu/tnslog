<template>
  <div id="carouselExampleControls" class="carousel slide carousel-container" data-ride="carousel">
    <div class="carousel-inner">
      <div class="carousel-item active">
        <img class="d-block w-100" src="https://tnslog.com.my/wp-content/uploads/2016/05/homeslider_1.jpg" alt="First slide">
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="https://tnslog.com.my/wp-content/uploads/2016/05/homeslider_2.jpg" alt="Second slide">
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="https://tnslog.com.my/wp-content/uploads/2016/05/homeslider_3-1.jpg" alt="Third slide">
      </div>
      <div class="carousel-item">
        <img class="d-block w-100" src="https://tnslog.com.my/wp-content/uploads/2016/05/homeslider_4-new-1.jpg" alt="Third slide">
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
  }
</style>