<!-- 
Linechart using Graph.js for Vue
-->

<script>
import { Line } from 'vue-chartjs'

export default {
    extends: Line,
    data: function() {
        return{
            labels: ['Tested', 'Positive', 'Deaths'],
            chartdata: [40,20,30]
        };
    },
    mounted () {
        this.renderChart(this.chartdata, this.options)
    }
    
}
</script>

<style lang="less" scoped>

</style>
