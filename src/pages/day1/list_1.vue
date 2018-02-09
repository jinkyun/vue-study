<template>
  <div id="app">
      <ul>
        <li v-for="n in 10">{{11-n}}</li>
        <li>launch missile!</li>
      </ul>
  </div>
</template>

<script>
import Vue from 'vue'
export default new Vue({el:'#app'})
</script>

<style lang="scss">

</style>
