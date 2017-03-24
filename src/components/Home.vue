<template>
  <div class='home'>
    这是主页
    {{count}}
    <button @click='increment'>+</button>
    <button @click='decrement'>-</button>
  </div>
</template>

<script>
  export default {
    name: 'home',
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
    }
  }
</script>

<style lang="scss">

</style>
