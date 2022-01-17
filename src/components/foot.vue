<template>
  <div class="foot">
    <div class="foot_con">
      <div class="left_tit">
        <a><img src="../../src/assets/img/AROTY.png"></a>
      </div>
      <p class="left_tit_p">There are many variations of passages of Lorem lpsum available,but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable.</p>
      <button class="btn_item1"><i></i></button>
      <button class="btn_item2"><i></i></button>
      <button class="btn_item3"><i></i></button>
      <button class="btn_item4"><i></i></button>

      <div class="mid_tit">
        <h3>Useful Links</h3>
      </div>
      <ul class="foot_list">
        <li class="rig_margin"><a href="#">Home</a></li>
        <li><a href="#">Cart</a></li>
        <li class="rig_margin"><a href="#">Man fashion</a></li>
        <li><a href="#">Checkout</a></li>
        <li class="rig_margin"><a href="#">Woman fashion</a></li>
        <li><a href="#">My Account</a></li>
        <li class="rig_margin"><a href="#">Accessories </a></li>
        <li><a href="#">Ourder Tracking</a></li>
        <li class="rig_margin"><a href="#">Collection</a></li>
        <li><a href="#">Privacy Policy</a></li>
      </ul>

      <div class="rig_tit">
        <h3>Contact Us</h3>
      </div>
      <div class="rig_link">
        <div class="left_icon_link">
          <a class="link_h"><img src="../../src/assets/img/foot/right-01.png"></a>
          <a class="link_m"><img src="../../src/assets/img/foot/right-02.png"></a>
          <a class="link_f"><img src="../../src/assets/img/foot/right-03.png"></a>
        </div>
        <div class="rig_text_link">
          <a class="text_a">622 Dixie Path,South Tobinches-ter~UT98336</a>
          <a class="text_b">+149-845-9488</a>
          <a class="text_c">Examlple@email.com</a>
        </div>
        <div class="foot_icon">
          <li><a><img src="../../src/assets/img/foot/foot-i-01.png"></a></li>
          <li><a><img src="../../src/assets/img/foot/foot_i_02.png"></a></li>
          <li><a><img src="../../src/assets/img/foot/foot_i_03.png"></a></li>
          <li><a><img src="../../src/assets/img/foot/foot_i_04.png"></a></li>
          <li><a><img src="../../src/assets/img/foot/foot_i_05.png"></a></li>
        </div>
      </div>


    </div>

  </div>
</template>

<script>
export default {
  name: "foot"
}
</script>

<style scoped>
.foot{
  width: 100%;
  height: 386px;
  background: #ffffff;
}
.foot_con{
  width: 1853px;
  height: 386px;
  margin: 0 auto;
  position: relative;
}
.foot_con .left_tit {
  width:187px;
  height: 48px;
  position: absolute;
  left: 336px;
  top:73px
}
.left_tit_p{
  width: 350px;
  height: 156px;
  padding: 15px 0px 13px 0px;
  position: absolute;
  left: 336px;
  top:120px;
}
.foot_con button{
  width: 46px;
  height: 46px;
  border-radius: 23px;
}
.btn_item1{
  background: #3b5999;
  position: absolute;
  left: 345px;
  top:280px;
}
.btn_item1 i{
  width: 16px;
  height: 16px;
  margin: 0 auto;
  display: block;
  background: url("../../src/assets/img/foot/foot_btn-01.png") no-repeat;
}
.btn_item2{
  background: #dd4b39;
  position: absolute;
  left: 399px;
  top:280px;
}
.btn_item2 i{
  width: 16px;
  height: 16px;
  margin: 0 auto;
  display: block;
  background: url("../../src/assets/img/foot/foot_btn-02.png") no-repeat;
}
.btn_item3{
  background: #55acee;
  position: absolute;
  left: 452px;
  top:280px;
}
.btn_item3 i{
  width: 16px;
  height: 16px;
  margin: 0 auto;
  display: block;
  background: url("../../src/assets/img/foot/foot_btn-03.png") no-repeat;
}
.btn_item4{
  background: #e4405f;
  position: absolute;
  left: 507px;
  top:280px;
}
.btn_item4 i{
  width: 16px;
  height: 16px;
  margin: 0 auto;
  display: block;
  background: url("../../src/assets/img/foot/foot_btn-04.png") no-repeat;
}

.mid_tit{
  width: 148px;
  height: 40px;
  text-align: center;
  position: absolute;
  left: 734px;
  top:73px;
}
.mid_tit h3{
  height: 20px;
  font-size: 19px;
  line-height: 19px;
  color: #333333;
  margin-top: 10px;
  margin-bottom: 10px;
}

.foot_list{
  width: 297px;
  height: 205px;
  padding: 20px 0px;
  position: absolute;
  top:120px;
  left: 735px;
}
.foot_list li{
  width: 131px;
  height: 22px;
  float: left;
  margin-bottom: 14px;
  /*margin-right: 32px;*/
}
.rig_margin{
  margin-right: 32px;
}
.foot_list li a{
  color: #666666;
}
.rig_tit{
  width: 125px;
  height: 39px;
  font-size: 18px;
  position: absolute;
  left: 1132px;
  top:73px
}
.rig_link{
  width: 338px;
  height: 205px;
  position: absolute;
  left: 1132px;
  top: 120px;
}
.left_icon_link{
  width: 36px;
  height: 127px;
  display: flex;
  flex-direction: column;
  align-content: space-between;
  margin-left: 0px;
  margin-top: 25px;
}
.link_h{
  width: 36px;
  height: 49px;
}
.link_h img{
  margin: 0px 3px 0px 0px;
}
.link_m{
  width: 36px;
  height: 50px;
}

.link_m img {
  margin: 10px 3px 10px 0px;
}
.link_f{
  width: 36px;
  height: 30px;
}
.link_f img{
  margin: 0px 3px 0px 0px;
}
.rig_text_link{
  width: 303px;
  height: 127px;
  position: absolute;
  left: 23px;
  top: 18px;
  color: #666666;
}
.text_a{
  display: block;
  width: 320px;
  height: 49px;
  font-size: 15px;
  padding: 6px 6px 6px 6px;
}
.text_b{
  display: block;
  width: 303px;
  height: 30px;
  padding: 6px 6px 6px 6px;
}
.text_c{
  display: block;
  width: 303px;
  height: 30px;
  padding:0px 6px 0px 6px;
}
.foot_icon{
  width: 232px;
  height: 25px;
  position: absolute;
  left: 0px;
  top:163px;
  display: flex;
  flex-direction: row;
  align-content: space-between;
}
.foot_icon a{
  margin-right: 8px;
}
</style>