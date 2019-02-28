<template>
  <div id="app">
    <CodeMirror></CodeMirror>
  </div>
</template>

<script>
import CodeMirror from '../../index.vue'

export default {
  name: 'app',
  components: {
    CodeMirror
  }
}
</script>

<style>
body {
    font-family: Roboto,sans-serif;
    background-color: #424242;
    color: white;
}
</style>
