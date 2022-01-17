<template>
  <div class="product">
    <div class="pro_con">
      <div class="pro_tit">
        <h3>Check Out Products</h3>
      </div>
      <div class="pro_list">
        <ul class="list_con">
          <li>
            <a href="#">
              <img src="../../src/assets/img/product/product-01.png">
            </a>
            <div class="txt_con">
              <h3>Active Fleece Pants</h3>
              <span class="old_pic">$14.95</span>
              <span class="new_pic">$10.00</span>

            </div>
          </li>

          <li>
            <a href="#"><img src="../../src/assets/img/product/product-02.png"></a>
            <div class="txt_con">
              <h3>Active Fleece Pants</h3>
              <span class="new_pic1">$17.00</span>
            </div>
          </li>

          <li>
            <a href="#"><img src="../../src/assets/img/product/product-03.png"></a>
            <div class="txt_con">
              <h3>Active Fleece Pants</h3>
              <span class="new_pic1">$6.29</span>
            </div>
          </li>

          <li>
            <a href="#"><img src="../../src/assets/img/product/product-04.png"></a>
            <div class="txt_con">
              <h3>Active Fleece Pants</h3>
              <span class="new_pic1">$4.50</span>
            </div>
          </li>
          <li>
            <a href="#"><img src="../../src/assets/img/product/product-05.png"></a>
            <div class="txt_con">
              <h3>Active Fleece Pants</h3>
              <span class="new_pic1">$16.00</span>
            </div>
          </li>

          <li>
            <a href="#"><img src="../../src/assets/img/product/product-06.png"></a>
            <div class="txt_con">
              <h3>Active Fleece Pants</h3>
              <span class="new_pic1">$58.00</span>
            </div>
          </li>
          <li>
            <a href="#"><img src="../../src/assets/img/product/product-07.png"></a>
            <div class="txt_con">
              <h3>Active Fleece Pants</h3>
              <span class="new_pic1">$63.00</span>
            </div>
          </li>
          <li>
            <a href="#"><img src="../../src/assets/img/product/product-08.png"></a>
            <div class="txt_con">
              <h3>Active Fleece Pants</h3>
              <span class="new_pic1">$62.00</span>
            </div>
          </li>
          <li>
            <a href="#"><img src="../../src/assets/img/product/product-09.png"></a>
            <div class="txt_con">
              <h3>Active Fleece Pants</h3>
              <span class="old_pic">$51.00</span>
              <span class="new_pic">$41.00</span>
            </div>
          </li>
          <li>
            <a href="#"><img src="../../src/assets/img/product/product-10.png"></a>
            <div class="txt_con">
              <h3>Active Fleece Pants</h3>
              <span class="new_pic1">$60.00</span>
            </div>
          </li>

          <li>
            <a href="#"><img src="../../src/assets/img/product/product-11.png"></a>
            <div class="txt_con">
              <h3>Active Fleece Pants</h3>
              <span class="new_pic1">$87.00</span>
            </div>
          </li>
          <li>
            <a href="#"><img src="../../src/assets/img/product/product-12.png"></a>
            <div class="txt_con">
              <h3>Active Fleece Pants</h3>
              <span class="new_pic1">$45.00</span>
            </div>
          </li>
          <li>
            <a href="#"><img src="../../src/assets/img/product/product-13.png"></a>
            <div class="txt_con">
              <h3>Active Fleece Pants</h3>
              <span class="new_pic1">$93.00</span>
            </div>
          </li>
          <li>
            <a href="#"><img src="../../src/assets/img/product/product-14.png"></a>
            <div class="txt_con">
              <h3>Active Fleece Pants</h3>
              <span class="old_pic">$51.00</span>
              <span class="new_pic">$41.00</span>
            </div>
          </li>
          <li>
            <a href="#"><img src="../../src/assets/img/product/product-15.png"></a>
            <div class="txt_con">
              <h3>Active Fleece Pants</h3>
              <span class="new_pic1">$56.00</span>
            </div>
          </li>


        </ul>

      </div>
      <div class="btn_con">
        <button class="pro_btn">VIEW ALL PRODUCT</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "product"
}
</script>

<style scoped>
.product{
  width: 100%;
  height: 2180px ;
  background: #ffffff;
}
.pro_con{
  display: flex;
  flex-flow: wrap;
  width: 1753px;
  height: 2180px;
  margin: 0 auto;
  padding: 0px 50px 0px 50px;
}
.product .pro_tit{
  width: 100%;
  height: 164px;
  /*margin-bottom: 0px;*/
  background: #ffffff
}
.pro_tit h3{
  margin: 66px 646px ;
  width: 460px;
  height: 30px;
  font-weight: 700;
  text-align: center;
  line-height: 30px;
  font-size: 30px;
}
.pro_list{
  width: 1754px;
  height: 1757px;
}
.list_con{
  display: flex;
  flex-flow: wrap;
  justify-content: space-between;
  width: 1754px;
  height: 1757px;
}
.list_con li{
  width: 336px;
  height: 533px;
}
.list_con a img{
  width: 336px;
  height: 447px;
}
.list_con .new_pic{
  width: 54px;
  height: 17px;
  font-size: 17px;
  line-height: 17px;
  color: #666666;
}
.txt_con{
  width: 196px;
  height: 58px;
  margin: 26px 70px 14px 70px;
  position: relative;

}
.txt_con h3{
  width: 187px;
  height: 16px;

  text-align: center;
  line-height: 16px;
  font-size: 16px;
  color: #333333;

  margin:  0px 12px 0px 12px;
}
.list_con .old_pic{
  color: #cccccc;
  width: 57px;
  height: 17px;
  font-size: 17px;
  line-height: 17px;
  text-decoration:line-through;
  position: absolute;
  left: 40px;
  right: 0px;
  top:42px;
  bottom: 14px;
}
.list_con .new_pic{
  width: 57px;
  height: 17px;
  font-size: 17px;
  line-height: 17px;
  position: absolute;
  left: 97px;
  right: 0px;
  top:42px;
  bottom: 14px;
}
.list_con .new_pic1{
  width: 57px;
  height: 17px;
  font-size: 17px;
  line-height: 17px;
  position: absolute;
  left: 69px;
  right: 69px;
  top:42px;
  bottom: 14px;
}
.btn_con{
  width: 1853px;
  height: 260px;
  padding: 0px 50px 0px 50px;
  position: relative;
}
.btn_con .pro_btn{
  display: block;
  background: #f1593b;
  color: #ffffff;
  width: 249px;
  height: 62px;
  border-radius: 5px;
  /*margin: 71px 753px 129px 754px;*/
  text-align: center;
  font-size: 14px;
  position: absolute;
  top:71px;
  right: 753px;
  bottom: 129px;
  left: 754px;
}

</style>