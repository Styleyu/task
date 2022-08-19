<template>
  <div>
    <div class=intro>
  
    <div class="head w">
      <!-- logo -->
      <div class="logo">
        <i>>_</i>
        Logo
      </div>

      <!-- 导航栏 -->
      <div class="nav">
          <ul>
              <li><a href="#">基本资料</a></li>
              <li><a href="#">项目经验</a></li>
              <li><a href="#">专业技能</a></li>
              <li><a href="#">工作经历</a></li>
              <li><a href="#">自我评价</a></li>
              <li><a href="#">联系方式</a></li>
          </ul>
      </div>
    </div>
  </div>
  </div>
</template>

<script>

export default {

}
</script>

<style lang="less" scoped>

.w {
    width: 1170px;
    margin: 0 auto;
}

ul li {
  list-style: none;
}

a {
      text-decoration: none;
      color: rgb(255, 255, 255);
}

* {
      margin : 0;
      padding: 0;
}

.intro{
  position: fixed;
  display: table;
  width: 100%;
  height: 100%;
  text-align: center;
  background: url(../assets/intro-bg.jpg) no-repeat bottom center;
  background-size: cover;
}

.head{
  height: 63px;
  padding: 12px 0px;
}

.logo{
  float: left;
  line-height: 63px;
  padding: 12px 15px;
  color: rgb(255, 255, 255);
  font-weight: 600;
  i{
     color: rgb(244, 208, 63);
  }
 
}

.nav{
  float: left;
  margin-left: 423px;

  ul li {
  float: left;
  padding: 0px 19px;
  line-height: 63px;
  }

  a:hover{
    color: rgb(244, 208, 63);
  }
}




</style>