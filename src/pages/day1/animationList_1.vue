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

var counter = 10;

var vm = new Vue({
  el:'#app',
  data : {
    countdown : []
  }
})

setInterval(function(){
  if ( counter > 0 ) {
    vm.countdown.push(counter--)
  }
},1000)

/* export var counter = 10;
export var vm = new Vue({
  el:'#app',
  data : {
    countdown : []
  }
})

 */
</script>

<style lang="scss">

</style>
