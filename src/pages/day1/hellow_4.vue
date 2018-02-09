<template>
  <div id="app">
     We conquered {{ countWorlds }} planets. <br/> Hello {{ countWorlds }} worlds
  </div>
</template>

<script>
import Vue from 'vue'

export default {
  name: 'app',
  data () {
    return {
      countWorlds : 5 + 2
    }
  }
}

/* export default new Vue({
    el:'#app',
    data : {
      countWorlds : 5 + 2
    }
  }) */
</script>

<style lang="scss">

</style>