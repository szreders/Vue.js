<template>
  <div id="app">
    <div id="nav">
      <router-link to="/home">Home</router-link>
      <router-link to="/about">About</router-link>
      <search/>
    </div>
    <router-view/>
  </div>
</template>

<style lang="scss">

</style>
<script>
  import Search from './views/Search';

  export default {
    components: {Search}
  }
</script>
