<template>
  <div class='nav'>
    <ul>
      <router-link tag='li' to='/' exact><a>主页</a></router-link>
      <router-link tag='li' to='/back'><a>第一类</a></router-link>
      <router-link tag='li' to='/hello/foo'><a>第二类</a></router-link>
      <router-link tag='li' to='/store'><a>第三类</a></router-link>
    </ul>
  </div>
</template>

<script>
  export default {
    name: 'nav'
  }
</script>

<style lang="scss">
.nav {
  ul{
    display: flex;
    li{
      display: inline-block;
      flex: 1;
      a{
        color: #333
      }
      &.active{
        a{
          color: red;
        }
      }
    }
  }
}
</style>
