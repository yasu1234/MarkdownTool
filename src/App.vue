<template>
  <div id="app">
    <markDownList msg="Markdown List"/>
  </div>
</template>

<script>
import markDownList from './components/markDownList.vue'

export default {
  name: 'App',
  components: {
    markDownList
  }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
