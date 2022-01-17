<template>
  <div id="app">

<!--    顶部标题-->
    <toptit />
<!-- 顶部导航栏-->
    <headnav />
<!--  轮播图  -->
    <Swiper />
<!--  推荐   -->
    <recommend />
<!--  商品列表  -->
    <product />
<!--  newsletter-->
    <news />
<!--    底部图片-->
    <foot-pic />
<!--底部-->
     <foot />
    <!--copyright-->
    <copyright />

  </div>

</template>

<script>

import toptit from "@/components/toptit";
import headnav from "@/components/headnav";
import Swiper from "@/components/swiper";
import Recommend from "@/components/recommend";
import Product from "@/components/product";
import News from "@/components/news";
import FootPic from "@/components/foot-pic";
import Foot from "@/components/foot";
import Copyright from "@/components/copyright";
export default {
  name: 'App',
  components: {
    Copyright,
    Foot,
    FootPic,
    News,
    Product,
    Recommend,
    Swiper,
    toptit,
    headnav,
  },

}
</script>

<style>
@import "assets/base.css";

</style>
