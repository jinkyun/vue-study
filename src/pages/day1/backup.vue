<template>
  <div id="app">
      <h1>{{ title }}</h1>
      <ul>
        <li v-for="(page, i) in pages">
          <a> {{ page }} </a>
        </li>
      </ul>
  </div>
</template>

<script>
export default {
  name: 'app',
  data () {
    return {
      title: 'Hara Study Day-1',
      pages : ['hellow','list','animationList']
    }
  }
}
</script>

<style lang="scss">

</style>
