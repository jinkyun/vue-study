<template>
  <div id="app">
      <ul>
        <li v-for="n in countdown">{{n}}</li>
        <li>launch missile!</li>
      </ul>
  </div>
</template>

<script>
import Vue from 'vue'

export default {
  name: 'app',
  data () {
    return {
      countdown : [10,9,8,7,6,5,4,3,2,1]
    }
  }
}

/* export default new Vue({
  el:'#app',
  data : {
    countdown : [10,9,8,7,6,5,4,3,2,1]
  }
}) */
</script>

<style lang="scss">

</style>
