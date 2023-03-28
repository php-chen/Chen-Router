<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">

    <div id="main">
      <h1>使用Echarts</h1>

    </div>
  </div>
</template>

<script>

// @ is an alias to /src
import HelloWorld from '@/components/HelloWorld.vue'
//引入
// import * as echarts from 'echarts';

//准备用于显示的元素节点
// setTimeout(function(){
// var myChart = echarts.init(document.getElementById('main'));
// //导入数据
//  myChart.setOption({
//    title: {
//     text: 'ECharts 入门示例'
//   },
//   tooltip: {},
//   xAxis: {
//     data: ['衬衫', '羊毛衫', '雪纺衫', '裤子', '高跟鞋', '袜子']
//   },
//   yAxis: {},
//   series: [
//     {
//       name: '销量',
//       type: 'bar',
//       data: [5, 20, 36, 10, 10, 20]
//     }
//   ]
//  })
// },16.7)




export default {
  name: 'home',
  components: {
    HelloWorld
  }
}
</script>
<style lang="css" scoped>
#main {
  width: 900px;
  height: 400px;
  border: 1px solid red;
}
</style>