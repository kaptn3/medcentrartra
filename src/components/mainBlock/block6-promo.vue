<template>
<div class="block-6">
  <h1>Акции и скидки</h1>
  <p class="description">У нас всегда есть выгодные скидки и спецпредложения для наших клиентов!</p>
  <div class="tickets">
    <div class="ticket-1">
      <img :src="require('../../assets/img/edge-left.png')" alt="sss">
      <div class="promo-text-1">
        <p class="t1">медицинский центр «Артра»</p>
        <p class="t2"> бесплатное кинезиотестирование</p>
        <img :src="require('../../assets/img/logo-mini.png')" alt="logo" >
      </div>
      <img :src="require('../../assets/img/edge-right.png')" alt="sss">
    </div>
    <img :src="require('../../assets/img/divider-wrap.png')" alt="wrap">
    <div class="ticket-2">
      <img :src="require('../../assets/img/edge-left.png')" alt="sss">
      <div class="promo-text-2">
        <p class="t1">медицинский центр «Артра»</p>
        <p class="t2">скидка 15% на курсовой массаж</p>
        <img :src="require('../../assets/img/logo-mini.png')" alt="logo" >
      </div>
      <img :src="require('../../assets/img/edge-right.png')" alt="sss">
    </div>

  </div>
  <div class="quote-wrap">
    <img :src="require('../../assets/img/Start.png')" alt="quote" class="start">

    <div class="quote">
      <p class="task">Наши цены прекрасны и без акций. Мы не навязываем лишних расходов, и всегда обсуждаем стоимость лечения с пациентами.</p>
      <div class="review-author">
        <div class="ellipse"></div>
        <div class="name-author">
          <p class="name">Егор Гудалов</p>
          <p class="post">директор медицинского центра «Артра»</p>
        </div>
      </div>

    </div>
  </div>
  <img :src="require('../../assets/img/End.png')" alt="quote" class="end">


</div>
</template>

<script>
export default {
  name: "block6-promo"
}
</script>

<style scoped>
.block-6{
  display: flex;
  flex-direction: column;
  align-items: center;

  margin: 80px 0;
}
h1{
  font-family: 'OnestMedium',serif;
  font-style: normal;
  font-weight: 700;
  font-size: 48px;
  line-height: 61px;

  color: #FFB341;
}
.description{
  width: 1280px;

  margin: 40px 0;

  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 500;
  font-size: 28px;
  line-height: 36px;

}
.tickets{

  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: flex-start;
  margin: 0 191px;
  gap: 60px;

}
.ticket-1{
  display: flex;
  flex-direction: row;
  align-items: flex-start;
}
.promo-text-1{
  width: 478px;
  height: 210px;

  background: #FFB341;

  display: flex;
  flex-direction: column;

  align-items: center;

}
.promo-text-1 .t1{
  height: 18px;

  margin: 20px 0;

  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 300;
  font-size: 14px;
  line-height: 18px;

  color: #000000;
  opacity: 0.2;
}
.promo-text-1 .t2{
  width: 398px;
  height: 92px;

  margin: 0 40px 20px;

  font-family: 'Onest';
  font-style: normal;
  font-weight: 700;
  font-size: 36px;
  line-height: 46px;

  color: #222222;

}
.promo-text-1 img{
  opacity: 0.2;
}
.ticket-2{
  width: 400px;
  height: 210px;

  display: flex;
  flex-direction: row;
  align-items: flex-start;
}
.promo-text-2{
  width: 478px;
  height: 210px;

  background: #FFB341;

  display: flex;
  flex-direction: column;

  align-items: center;

}
.promo-text-2 .t1{
  height: 18px;

  margin: 20px 0;

  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 300;
  font-size: 14px;
  line-height: 18px;

  color: #000000;
  opacity: 0.2;
}
.promo-text-2 .t2{
  width: 325px;
  height: 92px;

  margin: 0 40px 20px;

  font-family: 'Onest';
  font-style: normal;
  font-weight: 700;
  font-size: 36px;
  line-height: 46px;

  color: #222222;

}
.promo-text-2 img{
  opacity: 0.2;
}
.quote-wrap{
  width: 1280px;
  height: 332px;

  display: flex;
  flex-direction: column;
  align-items: flex-start;
  padding: 60px 0px 0px;
  margin-top: 40px;


}
.quote{
  width: 1280px;
  height: 272px;

  display: flex;
  flex-direction: column;
  align-items: center;
  padding: 40px;

  background-color: #FFB341;
  border-radius: 10px;
}
.task{
  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 500;
  font-size: 28px;
  line-height: 36px;

  color: #222222;
}
.review-author{
  display: flex;
  flex-direction: row;
  align-items: center;
  margin-top: 40px;
  gap: 20px;

  width: 460px;
  height: 80px;
}
.ellipse{
  width: 80px;
  height: 80px;

  background: #D9D9D9;
  border-radius: 50%;
}
.name{
  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 700;
  font-size: 36px;
  line-height: 46px;

  color: #222222;
}
.post{
  width: 360px;

  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 400;
  font-size: 18px;
  line-height: 23px;
  color: #222222;
}
.start{
  position: relative;
  top:15px;
  left: 130px;

}
.end{
  position: relative;
  bottom:15px;
  left: 530px;
}

</style>