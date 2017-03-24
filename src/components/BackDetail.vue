<template>
  <div class="back">
    <router-link to='/back'>返回</router-link>
    <div>我是路由详情示例/子路由示例</div>
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
body{
  transform: translate(0,0);
  h1, h2 {
    font-weight: normal;
  }
}

ul {
  list-style-type: none;
  padding: 0;
}

li {
  display: inline-block;
  margin: 0 10px;
}

a {
  color: #42b983;
}
</style>
