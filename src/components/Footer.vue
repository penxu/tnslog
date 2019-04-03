<template>
  <div class="footer-container">
    <footer class="site-footer" role="contentinfo">   
      <div class="copyright">
            © TNS Logistic Service Sdn Bhd 2016. All Rights Reserved. Powered by penxu WebDesign    </div>
    </footer>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
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

</style>
