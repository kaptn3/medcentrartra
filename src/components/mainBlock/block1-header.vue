<template>
<div class="header-content">
  <div class="text">
    <p>медицинский центр</p>
    <h1>артра</h1>
    <button>записаться на приём</button>
  </div>
</div>
</template>

<script>
export default {
  name: "block1-header"
}
</script>

<style scoped>
.header-content{
  height: 1024px;
  background: url("../../assets/img/bg-header.jpg") no-repeat;
  background-size: 1640px 1024px;
}
.text{
  display: flex;
  position: relative;
  top:260px;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}
p{
  font-family: 'OnestRegular';
  font-style: normal;
  font-weight: 500;
  font-size: 48px;
  line-height: 61px;
  display: flex;
  align-items: center;
  text-align: center;
  justify-content: center;

  /* white 1 */
  color: #EEEEEE;

  position: relative;
  height: 61px;

}
h1{
  position: relative;

  font-family: 'Onest';
  font-style: normal;
  font-weight: 900;
  font-size: 340px;
  line-height: 433px;
  /* identical to box height */

  display: flex;
  align-items: center;
  text-align: center;
  text-transform: uppercase;
  /* orange 1 */
  color: #FFBF5F;
}
button{
  background: #EEEEEE;
  border-radius: 20px;
  border: none;

  display: flex;
  align-items: center;
  text-align: center;

  color: #222222;

  font-family: 'OnestMedium';
  font-style: normal;
  font-weight: 500;
  font-size: 30px;
  line-height: 46px;
  padding: 10px 30px;
  margin-top: 150px;
}
button:hover{
  background: #DDDDDD;
}
button:active{
  background-color: #FFBF5F;
}
</style>