<template>
  <div id="app">
    <HeaderComp></HeaderComp>
    <div class="content">
      <ContentComp/>
    </div>
    <div class="hero">
      <HeroComp/>
    </div>
  </div>
</template>

<script>
import HeroComp from './components/HeroComp.vue'
import ContentComp from './components/ContentComp.vue'
import HeaderComp from './components/HeaderComp.vue'
export default {
  name: 'App',
  components: {
    HeaderComp,
    ContentComp,
    HeroComp,
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
</style>
