<template>
<div class="text">
  <h1>О нашей клинике</h1>
  <p>Основной профиль работы нашей клиники – это лечение пациентов с заболеваниями опорно-двигательного аппарата.<br><br>
    В нашей клинике мы применяем самые современные методы лечения, которые помогут Вам быстро вернуться к активному образу жизни и решить Вашу проблему.<br><br>
    У нас уютно, но без лишних расходов на интерьер, чтобы не завышать цены!</p>
  <button>подробнее</button>
</div>
</template>

<script>
export default {
  name: "block3-about"
}
</script>

<style scoped>
.text{
  display: flex;
  flex-direction: column;
  align-items: center;
  margin-top: 80px;
}
h1{
  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 700;
  font-size: 48px;
  line-height: 61px;

  color:#FFB341;
}

p{
  margin: 40px 80px;
  text-align: justify;

  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 500;
  font-size: 28px;
  line-height: 36px;
  display: flex;
  align-items: center;

  color: #222222;
}
button{
  padding: 10px 30px;
  border-radius: 20px;
  border: none;

  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 500;
  font-size: 36px;
  line-height: 46px;
}

button:hover{
  background: #DDDDDD;
}
button:active{
  background-color: #FFBF5F;
}


</style>