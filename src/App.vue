<template>
  <div id="app">
    <HeaderComp></HeaderComp>
    <div class="content">
      <ContentComp/>
    </div>
    <div class="hero">
      <HeroComp/>
    </div>
    <div class="bgMain">
      <div class="main">
      <MainComp/>
      <div class="photoContainer"></div>
    </div>
    </div>
    <div class="footer">
      <FooterComp/>
    </div>
  </div>
</template>

<script>
import FooterComp from './components/FooterComp.vue'
import MainComp from './components/MainComp.vue'
import HeroComp from './components/HeroComp.vue'
import ContentComp from './components/ContentComp.vue'
import HeaderComp from './components/HeaderComp.vue'
export default {
  name: 'App',
  components: {
    HeaderComp,
    ContentComp,
    HeroComp,
    MainComp,
    FooterComp,
  }
}
</script>

<style lang="scss">
*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  border-top: 30px solid black;
  border-bottom: 30px solid black;
  padding-top: 10px;
}
.content{
  background-color: black;
}
.hero{
  background-color: #0282F9;
}
.bgMain{
  background-image: url('assets/img/footer-bg.jpg');
  background-position: center;
  background-size: cover;
}
.main{
  display: flex;
  height: 300px;
  width: 80%;
  margin: auto;
  .photoContainer{
    background-image: url('assets/img/dc-logo-bg.png');
    height: 100%;
    width: 800px;
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
  }
}
.footer{
  background-color: #303030;
}
</style>
