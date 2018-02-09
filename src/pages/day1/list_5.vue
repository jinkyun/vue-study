<template>
  <div id="app">
      <ul>
        <li v-for="(sound, name) in animals">
          The {{name}} goes {{sound}}
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
      animals : {
      'dog': 'woof','cat':'meow','bird':'tweet'
      }
    }
  }
}

/* export default new Vue({
  el:'#app',
  data: {
    animals : {
      'dog': 'woof','cat':'meow','bird':'tweet'
    }
  }
}) */
</script>

<style lang="scss">

</style>
