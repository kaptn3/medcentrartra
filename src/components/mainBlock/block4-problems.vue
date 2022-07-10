<template>
<div class="block4">
  <h1>В нашем медицинском центре Вы не столкнетесь с такими проблемами, как</h1>
  <div class="problem-line-1">
    <img :src="require('../../assets/img/cross.png')" alt="sss" class="cross">
    <img :src="require('../../assets/img/line.png')" alt="sss" height="6px" class="line">
    <p>дорогое лечение</p>
    <img :src="require('../../assets/img/line.png')" alt="sss" height="6px" class="line">
    <p>некачественные медикаменты</p>
    <img :src="require('../../assets/img/join 1.png')" alt="sss" height="72px" class="join1">
  </div>
  <div class="problem-line-2">
    <img :src="require('../../assets/img/join 2.png')" alt="sss" height="72px" class="join2">
    <p>неэффективное лечение</p>
    <img :src="require('../../assets/img/line-long.png')" alt="sss" height="6px" class="line">
    <p>неопытные врачи</p>
  </div>
  <div class="problem-line-3">
    <p>равнодушные врачи</p>
    <img :src="require('../../assets/img/line-medium.png')" alt="sss" height="6px" class="line">
    <p>неясный бюджет</p>
    <img :src="require('../../assets/img/line-medium.png')" alt="sss" height="6px" class="line">
    <img :src="require('../../assets/img/cross.png')" alt="sss" class="cross">
  </div>
</div>
</template>

<script>
export default {
  name: "block4-problems"
}
</script>

<style scoped>
.block4{
  display: flex;
  flex-direction: column;
  margin: 80px 0;
}

h1{
  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 700;
  font-size: 48px;
  line-height: 61px;
  color: #FFB341;
  margin-bottom: 40px;
}
p{
  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 500;
  font-size: 36px;
  line-height: 46px;
}
.problem-line-1{
  display: flex;
  flex-direction: row;
  align-items: center;
  margin: 0 80px;
}
.problem-line-2{
  display: flex;
  flex-direction: row;
  align-items: center;
  margin: 0 80px;
}
.problem-line-3{
  display: flex;
  flex-direction: row;
  align-items: center;
  margin-left: 185px;
  padding-top: 10px;
}


.cross{
}

.join1{
  position: relative;
  margin-left: 20px;
  top: 35px;
}

.join2{
  position: relative;
  margin-right: 20px;
  top: 35px;
}


.line{
  margin-right: 20px;
  margin-left: 20px;
}
</style>