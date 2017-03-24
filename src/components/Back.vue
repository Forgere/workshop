<template>
  <div class="back">
    <router-link to='/back/details'>第一类详情</router-link>
    <div>这是路由示例</div>
    <router-view></router-view>
  </div>
</template>

<script>
export default {
  name: 'back',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
</style>
