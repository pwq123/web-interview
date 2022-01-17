<template>
  <div class="recommend">
    <div class="reco_con">
      <div class="left_item">
        <a href="#"><img src="../../src/assets/img/left-item.png"></a>
      </div>
      <div class="mid_item">
        <div class="item1">
          <a href="#"><img src="../../src/assets/img/item-01.png"></a>
        </div>
        <div class="item2">
          <a href="#"><img src="../../src/assets/img/item-02.png"></a>
        </div>

        <div class="item3">
          <a href="#"><img src="../../src/assets/img/item-03.png"></a>
        </div>
        <div class="item4">
          <a href="#"><img src="../../src/assets/img/item-04.png"></a>
        </div>
      </div>
      <div class="right_item">
        <a href="#"><img src="../../src/assets/img/right-item.png"></a>
      </div>
    </div>

  </div>
</template>

<script>
export default {
  name: "recommend"
}
</script>

<style scoped>
.recommend{
  width: 100%;
  height: 644px;
  background: #ffffff;
}
.reco_con{
  width: 1753px;
  height: 544px;
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  padding: 61px 50px;
  flex-direction: row;

}
.left_item{
  width: 418px;
  height: 524px;
  margin-left: 0px;
  margin-top: 0px;

}
.left_item  img{
  width: 418px;
  height: 524px;
}
.mid_item{
  width: 862px;
  height: 524px;
  display: flex;
  flex-direction: row;
  flex-wrap: wrap;
  /*margin-right: 20px;*/

}
.mid_item .item1{
  width:342px;
  height: 248px;
  margin-right: 30px;
}
.item1 a img{
  width:342px;
  height: 248px;
}
.mid_item .item2{
  width: 490px;
  height: 245px;
}
.item2 a img{
  width: 490px;
  height: 245px;
}
.mid_item .item3{
  width: 490px;
  height: 246px;
  margin-right: 30px;
  margin-top: 30px;
}
.item3 a img{
  width: 490px;
  height: 246px;
}
.mid_item .item4{
  width: 342px;
  height: 246px;
  margin-top: 33px;
}
.item4 a img{
  width: 342px;
  height: 246px;
}
.right_item{
  width: 416px;
  height: 524px;

}
.right_item img{
  width: 416px;
  height: 524px;
}


</style>