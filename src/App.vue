<template>
  <div id="app">
    <HeaderComp></HeaderComp>
  </div>
</template>

<script>

import HeaderComp from './components/HeaderComp.vue'
export default {
  name: 'App',
  components: {
    HeaderComp,
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
</style>
