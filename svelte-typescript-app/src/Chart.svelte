<script lang="ts">
    import * as echarts from "echarts";
let chart = echarts.init(<HTMLDivElement>document.getElementById("app"), {});

chart.setOption({
    title: {
        text: 'ECharts Getting Started Example'
    },
    tooltip: {},
    xAxis: {
        data: ['shirt', 'cardigan', 'chiffon', 'pants', 'heels', 'socks']
    },
    yAxis: {},
    series: [{
        name: 'sales',
        type: 'bar',
        data: [5, 20, 36, 10, 10, 20]
    }]
});


</script>
  
  <div id="main" style="width: 600px;height:400px;"></div>