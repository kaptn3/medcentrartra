<template>
  <div id="app">
    <header-wrap/>
    <main-content/>
    <block2-service/>
    <block3-about/>
    <block4-problems/>
    <block5-specialists/>
    <block6-promo/>
  </div>
</template>

<script>
import headerWrap from './components/header-wrap';
import mainContent from "@/components/mainContent";
import block2Service from "@/components/mainBlock/block2-service";
import block3About from "@/components/mainBlock/block3-about";
import block4Problems from "@/components/mainBlock/block4-problems";
import block5Specialists from "@/components/mainBlock/block5-specialists";
import block6Promo from "@/components/mainBlock/block6-promo";

export default {
  name: 'App',
  components: {
    headerWrap,
    mainContent,
    block2Service,
    block3About,
    block4Problems,
    block5Specialists,
    block6Promo
  }
}
</script>

<style>

@font-face {
  font-family: 'Onest';
  src: local("onest"), url("../public/fonts/onest/OnestBlack1602-hint.woff") format("woff");
}
@font-face {
  font-family: 'OnestRegular';
  src: local("onest"), url("../public/fonts/onest/OnestRegular1602-hint.woff") format("woff");
}
@font-face {
  font-family: 'OnestMedium';
  src: local("onest"), url("../public/fonts/onest/OnestMedium1602-hint.woff") format("woff");
}
*{
  margin: 0;
  padding: 0;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}
</style>
