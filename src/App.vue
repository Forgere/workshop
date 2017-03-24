<template>
  <div id="app">
    <Navs/>
    <router-view></router-view>
  </div>
</template>

<script>
import Navs from './components/Nav.vue'

export default {
  name: 'app',
  components: {Navs}
}
</script>

<style lang="scss">
#app {
  font-family:"Microsoft YaHei",Arial,Helvetica,sans-serif,"宋体";
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
