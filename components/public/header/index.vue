<template>
  <div>
    <top-bar></top-bar>
    <search-top></search-top>
  </div>
</template>

<script>
  import topBar from './topBar/index.vue'
  import searchBar from './searchBar/index.vue'
  export default {
    components: {
      topBar,
      searchBar
    }
  }
</script>

<style scoped>

</style>
