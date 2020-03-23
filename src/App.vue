<template>
  <div id="app">
    <h1> Heisann </h1>
    <div class="chart">
      <LineChart/>
    </div>
  </div>
</template>

<script>
import LineChart from './components/LineChart.vue'

export default {
  name: 'App',
  components: {
    LineChart,
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
#chart {
margin: 60px;
color: #2180ce;
height: 200px;
}
</style>
