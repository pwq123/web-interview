<template>
  <div class="foot_pic">
    <a><img src="../../src/assets/img/foot/foot-01.png"></a>
    <a><img src="../../src/assets/img/foot/foot-02.png"></a>
    <a><img src="../../src/assets/img/foot/foot-03.png"></a>
    <a><img src="../../src/assets/img/foot/foot-04.png"></a>
    <a><img src="../../src/assets/img/foot/foot-05.png"></a>
    <a><img src="../../src/assets/img/foot/foot-06.png"></a>
  </div>
</template>

<script>
export default {
  name: "foot-pic"
}
</script>

<style scoped>
.foot_pic{
  width: 1853px;
  height: 311px;
  margin: 0 auto;
}
.foot_pic  img{
  width: calc(100% / 6);
  height: 311px;
}
</style>