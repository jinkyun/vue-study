<template>
  <div id="app">
      <ul>
        <li v-for="(animal,i) in animals">
          The {{animal}} goes {{sounds[i]}}
        </li>
      </ul>
  </div>
</template>

<script>
import Vue from 'vue'

export default {
  name: 'app',
  data () {
    return {
      animals : ['dog','cat','bird'],
      sounds : ['woof','meow','tweet']
    }
  }
}

/* export default new Vue({
  el:'#app',
  data: {
    animals : ['dog','cat','bird'],
    sounds : ['woof','meow','tweet']
  }
}) */

</script>

<style lang="scss">

</style>
