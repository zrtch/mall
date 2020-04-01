<template>
  <div class="footer">
    <div class="footer-logo">
      <img src="/imgs/logo-footer.png" alt="">
      <p>小米商城</p>
    </div>
    <div class="footer-link">
      <a href="">godz主页</a><span>|</span>     
      <a href="">vue全栈课程</a><span>|</span>           
      <a href="">react全家桶课程</a><span>|</span>           
      <a href="">微信支付课程</a>      
    </div>
    <div class="copyright">
      Copyright ©2020<span class="domian">mi.futurefe.com</span> All Rights Reserved
    </div>
  </div>
</template>

<script>
export default {
name:'nav-footer'
}
</script>

<style lang="scss" scoped>
  .footer{
    height:234px;
    border-top:4px solid #ff6600;
    background-color:#333;
    color:#999;
    font-size:16px;
    text-align: center;
    .footer-logo{
      margin-top: 46px;
      margin-bottom: 31px;
      img{
        width:53px;
        height:36px;
        margin-bottom: 13px;
      }
    }
    .footer-link{
      a{
        color:#999;
        display: inline-block;
      }
      span{
        margin: 0 10px;
      }
      margin-bottom: 13px;
    }
    .copyright{
      .domian{
        color:#ff6600;
      }
    }
  }
  
</style>