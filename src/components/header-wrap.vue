<template>
  <div class="header-wrap">
    <nav>
      <ul>
        <li><a href="#">Услуги и цены</a></li>
        <li><a href="#">О клинике</a></li>
        <li><a href="#"><img :src=" require ('../assets/img/logo.svg')" alt="sss"></a></li>
        <li><a href="#">Оперативное лечение</a></li>
        <li><a href="#">Блог</a></li>
      </ul>
    </nav>
  </div>
</template>

<script>
export default {
  name: "header-wrap"
}
</script>

<style scoped>
.header-wrap{
  display: flex;
  justify-content: center;
  position: absolute;
  height: 110px;
  width: 100%;


}
nav{
  width: 1440px;
  position: relative;
  top: 20px;
}

ul{
  display: flex;

  justify-content: center;
  align-items: center;
  padding: 10px;
  gap: 10px;
  height: 70px;

  /* white 1 */

  background: #EEEEEE;
  border-radius: 10px;

  /* Inside auto layout */

}

li{
  width: 268px;
  height: 23px;
  /* identical to box height */

  display: flex;
  align-items: center;
  text-align: center;
  justify-content: center;

  /* black 2 */

  color: #222222;
}

a{
  text-decoration: none;
  font-family: 'Onest';
  font-style: normal;
  font-weight: 500;
  font-size: 18px;
  line-height: 23px;
  color:#222222;
}
</style>