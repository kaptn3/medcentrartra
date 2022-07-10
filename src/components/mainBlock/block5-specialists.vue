<template>
<div class="block5">
  <h1>Наши специалисты</h1>
  <p>У нас работают опытные специалисты с большим стажем работ, которые с радостью готовы помочь Вам в решении Вашей проблемы!</p>
  <div class="frames">
    <div class="frame-1">
      <img :src="require('../../assets/img/doctor-1.png')" alt="doctor" >
      <h1 class="doctorName">Василий Борисович Третьяков</h1>
      <p class="description">травматолог-ортопед высшей категории, кандидат медицинских наук</p>
    </div>
    <div class="frame-2">
      <img :src="require('../../assets/img/doctor-2.png')" alt="doctor" >
      <h1 class="doctorName">Анатолий Валерьевич Рожко</h1>
      <p class="description">кинезиомассажист</p>
    </div>
  </div>

</div>
</template>

<script>
export default {
  name: "block5-specialists"
}
</script>

<style scoped>
.block5{
  display: flex;
  flex-direction: column;
  align-items: center;
}

h1{
  font-family: 'OnestMedium',serif;
  font-style: normal;
  font-weight: 700;
  font-size: 48px;
  line-height: 61px;

  color: #FFB341;
}
p{
  width: 1280px;

  font-family: 'OnestMedium',serif;
  font-style: normal;
  font-weight: 500;
  font-size: 28px;
  line-height: 36px;

  margin: 40px 0;
}
.frames{
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  gap: 40px;
}
.frame-1{
  height: 614px;

  display: flex;
  flex-direction: column;
  align-items: center;

  background: #EEEEEE;
  border-radius: 30px;
}
.frame-2{
  height: 614px;

  display: flex;
  flex-direction: column;
  align-items: center;

  background: #EEEEEE;
  border-radius: 30px;
}
img{
  padding: 20px;
  border-radius: 30px;
}
.doctorName{
  width: 300px;

  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 700;
  font-size: 24px;
  line-height: 31px;
  text-align: center;

  color: #222222;
}
.description{
  width: 300px;

  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 400;
  font-size: 14px;
  line-height: 18px;
  text-align: center;

  color: #222222;

  margin: 6px 20px 20px 20px;
}
</style>