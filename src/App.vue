<template>
  <div id="app">
    <Chart msg="Welcome to Your Vue.js App"/>
  </div>
</template>

<script>
import Chart from './components/Chart.vue';

export default {
  name: 'app',
  components: {
    Chart,
  },
};
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
