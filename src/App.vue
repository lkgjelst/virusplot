<template>
  <div id="app">
    <h1> Heisann </h1>
    <div class="chart">
      <LineChart :styles="chartStyles"/>
    </div>
    <Footer/>
  </div>
</template>

<script>
import LineChart from './components/LineChart.vue'
// import Header from './components/Header.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    LineChart,
    Footer,
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
