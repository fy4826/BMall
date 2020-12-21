<template>
  <div class="footer">
    <div class="footer-logo">
      <img src="/imgs/logo-footer.png" alt="" />
      <p>B-MALL商城</p>
    </div>
    <div class="footer-link">
      <a href="https://github.com/fy4826" target="_blank">carbide的github主页</a
      ><span>|</span>
      <a
        href="https://fy4826.github.io/LemonMusic/dist/index.html"
        target="_blank"
        >LemonMusic(仿网易云音乐移动端)</a
      >
    </div>
    <div class="copyright">
      Copyright ©2020 <span class="domain">carbide.top</span> All Rights
      Reserved.
    </div>
  </div>
</template>
<script>
export default {
  name: "nav-footer",
};
</script>
<style lang='scss' scoped>
.footer {
  height: 234px;
  border-top: 4px solid #ff6600;
  background-color: #333;
  color: #999;
  font-size: 16px;
  text-align: center;
  .footer-logo {
    margin-top: 46px;
    margin-bottom: 31px;
    img {
      width: 53px;
      height: 36px;
      margin-bottom: 13px;
    }
  }
  .footer-link {
    a {
      color: #999;
      display: inline-block;
    }
    span {
      margin: 0 4px;
    }
    margin-bottom: 13px;
  }
  .copyright {
    .domain {
      color: #ff6600;
    }
  }
}
</style>