<template>
  <div class="main-block">
    <div class="text">
      <h1>Наши услуги</h1>
      <p class="first-paragraph">У нас Вы можете пройти полное лечение – от диагностики до эстетических процедур:</p>
    </div>
    <div class="service">
      <div class="row1">
        <button>Консультация травматолога-ортопеда</button>
        <button>Тканевая терапия Plasmolifting, PRP</button>
        <button>Лечение остеоартроза</button>
        <button>Классический и кинезиомассаж</button>
      </div>
      <div class="row2">
        <button>Лечение спортивной травмы</button>
        <button>Кинезио-тейпирование</button>
        <button>Артроскопия суставов</button>
        <button>Изготовление индивидуальных стелек</button>
      </div>
    </div>
    <div class="number">
      <div class="nRow1">
        <div class="number1">
          <p class="number1-p">35000+</p>
          <p class="number1-2p">успешно пролеченных пациентов</p>
        </div>
        <div class="number2">
          <p class="number2-p">12 000+</p>
          <p class="number2-2p">проведённых операций</p>
        </div>
      </div>
      <div class="nRow2">
        <div class="number3">
          <p class="number3-p">35 лет</p>
          <p class="number3-2p">опыта работы</p>
        </div>
        <div class="number4">
          <p class="number4-p">9 из 10</p>
          <p class="number4-2p">пациентов остаются на лечение</p>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "block2-service"
}
</script>

<style scoped>
.main-block{

  height: 853px;
}
.text{
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;

  margin-top: 80px;
}
h1{

  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 700;
  font-size: 48px;
  line-height: 61px;
  padding-bottom: 40px;

  color: #FFB341;
}
.first-paragraph{
  width: 1280px;
  height: 36px;

  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 500;
  font-size: 28px;
  line-height: 36px;

  padding-bottom: 40px;
}
.service{
  display: flex;
  flex-direction: column;
  align-items: center;
}
.row1{
  display: flex;
  flex-direction: row;
}
.row2{
  display: flex;
  flex-direction: row;
}
button{
  width: 312.5px;
  height: 109px;

  border-radius: 20px;
  border: none;

  margin-right: 10px;
  margin-bottom: 10px;

  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 500;
  font-size: 24px;
  line-height: 31px;

  background-color: #EEEEEE;
}
button:hover{background-color:#DDDDDD}
button:active{background-color:#FFBF5F}
.number{
  margin-top: 25px;
}
.nRow1{
  height: 204px;

  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.number1-p{
  color: #FFB341;
  text-align: left;
  margin-left: 96px;
  height: 204px;

  font-family: 'Onest';
  font-style: normal;
  font-weight: 800;
  font-size: 160px;
  line-height: 204px;
}
.number1-2p{
  text-align: left;
  margin-left: 136px;
  position: relative;
  bottom: 40px;

  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 700;
  font-size: 36px;
  line-height: 46px;
}
.number2-p{
  color: #FFB341;
  text-align: right;
  margin-right: 96px;

  font-family: 'Onest';
  font-style: normal;
  font-weight: 800;
  font-size: 160px;
  line-height: 204px;
}
.number2-2p{
  text-align: right;
  margin-right: 195px;
  position: relative;
  bottom: 40px;

  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 700;
  font-size: 36px;
  line-height: 46px;
}
.nRow2{
  height: 204px;
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
.number3-p{
  margin-left: 137px;
  color: #FFB341;

  font-family: 'Onest';
  font-style: normal;
  font-weight: 800;
  font-size: 160px;
  line-height: 204px;
}
.number3-2p{
  text-align: left;
  margin-left: 177px;
  position: relative;
  bottom: 40px;

  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 700;
  font-size: 36px;
  line-height: 46px;
}
.number4-p{
  text-align: right;
  margin-right: 240px;
  color: #FFB341;

  font-family: 'Onest';
  font-style: normal;
  font-weight: 800;
  font-size: 160px;
  line-height: 204px;
}
.number4-2p{
  text-align: right;
  margin-right: 137px;
  position: relative;
  bottom: 40px;

  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 700;
  font-size: 36px;
  line-height: 46px;
}

</style>