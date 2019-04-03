<template>
  <div class="navigation_bar">
        <div class="container clear">
          <div class="pull-left logo-box">
              <a href="./index.html" class="logo">
                  <img class="pc" src="https://tnslog.com.my/wp-content/uploads/2017/10/TNS-Logo.jpg">
              </a>
          </div>
            <div class="right_menu ">
              <ul class="nav justify-content-end">
                <li class="nav-item">
                  
                  <a class="nav-link active" href="#"><router-link to="/home">首页</router-link></a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#"><router-link to="/about">关于我们</router-link></a>
                </li>
                <li class="nav-item">
                  <a class="nav-link" href="#"><router-link to="/service">服务</router-link></a>
                </li>
                <li class="nav-item">
                  <a class="nav-link " href="#"> <router-link to="/contact">联系我们</router-link></a>
                </li>
              </ul>
            </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
  .navigation_bar {
    width: 100%;
    // position: fixed;
    padding-top: 10px;
    z-index: 999;
    transition: all .5s cubic-bezier(0,0,0,0.98);
    box-sizing: border-box;
    height: 70px;
    line-height: 70px;
    background: transparent;
    .container {
      margin-right: auto;
      margin-left: auto;
      height: 100%;
    }
  }

</style>