<template>
  <div class="news">
    <div class="news_con">
      <div class="news_tit">
        <h3>Newsletter</h3>
        <span>Get timely updates from your favorite products</span>
        <input class="emil-input" placeholder="You e-mail...">
        <button class="emil_btn"><i></i></button>
        <button class="pass_btn"><i></i></button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "news"
}
</script>

<style scoped>

.news{
  width: 100%;
  height: 363px;
  background: #ffffff;
}
.news_con{
  width: 1853px;
  height: 363px;
  margin: 0 auto;
  position: relative;
}
.news_con .news_tit h3{
  width: 249px;
  height: 31px;
  color: #333333;
  line-height: 31px;
  font-size: 31px;
  text-align: center;
  position: absolute;
  top:89px;
  left: 802px;
  right: 802px;
  bottom: 245px;
}
.news_tit span{
  width: 430px;
  height: 23px;
  font-size: 16px;
  line-height: 23px;
  color: #666666;
  text-align: center;
  position: absolute;
  left: 711px;
  right: 711px;
  top:141px;
  bottom: 200px;
}
.news_tit input {
  width: 700px;
  height: 45px;
  border: 1px solid #e5e5e5;
  position: absolute;
  left: 577px;
  top:209px;
  right: 577px;
  bottom: 111px;
}
.news_tit input::placeholder{
  color: #999999;
  font-size: 16px;
  padding-left: 30px;


}
.emil_btn{
  width: 13px;
  height: 10px;
  position: absolute;
  top:227px;
  left:592px
}
.emil_btn i{
  display: block;
  width: 13px;
  height: 10px;
  background: url("../../src/assets/img/emil.png");
}
.pass_btn{
  width: 67px;
  height: 45px;
  position: absolute;
  left: 1211px;
  top:209px;
  right: 577px;
  background: #f1593c ;
  border-bottom-right-radius: 5px;
  border-top-right-radius: 5px;
}
.pass_btn i{
  display: block;

  width: 30px ;
  height: 30px;
  margin: 0 auto;
  background: url("../../src/assets/img/poss.png");
}
</style>