<template>
  <div id="app">
    <Form1 msg="I'm Alvin"/>
  </div>
</template>

<script>
import Form1 from './components/Form1.vue'

export default {
  name: 'App',
  components: {
    Form1
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
