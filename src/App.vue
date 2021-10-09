<template>
  <div id="app">
    <AreaChart />
    <PieChart />
    <BarChart />
    <RadarChart />
    <LineChart />
  </div>
</template>

<script>
import AreaChart from "./components/AreaChart.vue";
import PieChart from "./components/PieChart.vue";
import BarChart from "./components/BarChart.vue";
import RadarChart from "./components/RadarChart.vue";
import LineChart from "./components/LineChart.vue";

export default {
  name: "App",
  components: {
    AreaChart,
    PieChart,
    BarChart,
    RadarChart,
    LineChart,
  },
  data() {
    return {
      chartData: {
        Books: 24,
        Magazine: 30,
        Newspapers: 10,
      },
    };
  },
};
</script>

<style>
#app {
  font-family: "Avenir", Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
