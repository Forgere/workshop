<template>
  <div class="hello">
    <router-link to='/back'>backs</router-link>
    <h1>动态路由示例</h1>
    <div>Name: {{$route.params.id}}</div>
  </div>
</template>

<script>
export default {
  name: 'hello',
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
