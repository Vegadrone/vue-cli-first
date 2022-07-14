<template>
  <div id="app">
    <Title />
    <jumbotron/>
  </div>
</template>

<script>
import Title from './components/Title.vue';
import Jumbotron from './components/Jumbotron.vue'

export default {
  name: 'App',
  components: {
    Title,
    Jumbotron,

  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #da296d;
  margin-top: 60px;
}
</style>
