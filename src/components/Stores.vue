<template>
  <div class="stores">
    <router-link to='/'>返回主页，查看鱼</router-link>
    <div>这是vuex示例</div>
    {{count}}
    <button @click='increment'>+</button>
    <button @click='decrement'>-</button>
  </div>
</template>

<script>
export default {
  name: 'store',
  computed: {
    count () {
      return this.$store.state.count
    }
  },
  methods: {
    increment () {
      this.$store.commit('increment')
    },
    decrement () {
      this.$store.commit('decrement')
    }
  },
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style lang="scss">
</style>
