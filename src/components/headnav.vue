<template>
  <div class="head">
    <div class="head_con">
      <div class="head_pic">
<!--        <a href="#"><img src="../src/assets/img/AROTY.png" alt=""></a>-->
        <a href="#"><img src="../../src/assets/img/AROTY.png" alt=""></a>
      </div>
      <ul class="nav_list">
        <li><a href="#" :style="active">HOME</a></li>
        <li><a href="#">SHOP</a></li>
        <li><a href="#">BLOG</a></li>
        <li><a href="#">PAGES</a></li>
        <li class="right_nav_item"><a href="#">CONTACT US</a></li>
      </ul>
      <div class="rig_item1"></div>
      <div class="rig_item2">
        <a href="#"><img src="../../src/assets/img/search.png"></a>
      </div>
      <div class="rig_item3">
        <a href="#"><img src="../../src/assets/img/cart.png"></a>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "head",

  data(){
    return{
      active:{
        color: '#f15990'
      }
    }

  }
}
</script>

<style scoped>
.head{
  width: 100%;
  height: 88px;
  /*background: gray;*/
  background: #ffffff;
}
.head_con{
  display: flex;
  flex-direction: row;
  flex-wrap: nowrap;
  width: 1853px;
  height: 88px;
  background: #ffffff;
  margin: 0 auto;
}
.head_pic{
  width: 159px;

  height: 41px;
  margin-left: 338px;
  margin-top: 23px;
  margin-bottom: 23px;
}
.head_pic a img{
  width: 159px;
  height: 41px;


}
.nav_list{
  overflow: hidden;
  margin-left: 466px;
}
.nav_list li{

  float: left;
  width: 47px;
  height: 16px;
  line-height: 16px;
  margin-top: 37px;
  margin-bottom: 36px;
  margin-right: 40px;
}
.nav_list .right_nav_item{
  width: 98px;
  margin-right: 18px;
}
.right_nav_item a{
  font-size: 16px;
  width: 98px;

}

.nav_list li a{
  display: block;
  white-space: nowrap;
  font-size: 16px;
}

.nav_list li a:hover{
  color: #f15990;
}
.rig_item1{

  margin-top: 26px;
  width: 1px;
  height: 27px;
  background-color: #c2c2c2;
}
.rig_item2{
  margin: 30px 14px 27px 14px;
  width: 24px;
  height: 24px;
}
.rig_item2 img{
  width: 24px;
  height: 24px;
}
.rig_item3{
  width: 34px;
  height: 33px;
  margin-top: 30px;
  margin-bottom: 26px;
}
.rig_item3 img{
  width: 34px;
  height: 33px;
}
</style>