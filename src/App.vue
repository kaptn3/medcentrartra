<template>
  <div id="app">
    <header-wrap/>
    <main-content/>
    <block2-service/>
    <HelloWorld msg="Welcome to Your Vue.js App"/>

  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import headerWrap from './components/header-wrap';
import mainContent from "@/components/mainContent";
import block2Service from "@/components/mainBlock/block2-service";

export default {
  name: 'App',
  components: {
    HelloWorld,
    headerWrap,
    mainContent,
    block2Service

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
