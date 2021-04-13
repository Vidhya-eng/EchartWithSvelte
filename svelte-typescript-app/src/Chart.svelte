<script type="text/javascript">
  import * as echarts from "echarts";

  window.onload = function () {
    let chart = echarts.init(document.getElementById("main"));

    chart.setOption({
      title: {
        text: "ECharts Getting Started Example",
      },
      tooltip: {},
      xAxis: {
        data: ["shirt", "cardigan", "chiffon", "pants", "heels", "socks"],
      },
      yAxis: {},
      series: [
        {
          name: "sales",
          type: "bar",
          data: [5, 20, 36, 10, 10, 20],
        },
      ],
    });
  };
</script>

<div id="main" style="width: 600px;height:400px;" />
