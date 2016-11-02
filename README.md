# pluIn_pieChart
在jQuery的基础上，做了一个画饼图的插件，只要传送数据即可

## 具体使用如下例子

```
<script>
    // 给第一个元素中绘制饼图
    $('div').css({
        marginTop: '10px',
        width: '500px',
        height: '500px',
        backgroundColor: 'blue'
    }).drawPieChart([
        {val: 2, msg: '糖饼数量'},
        {val: 5, msg: '馅饼数量'},
        {val: 10, msg: '酱香饼'},
        {val: 6, msg: '手抓饼'},
        {val: 3, msg: '煎饼果子来一套'},
    ], 100);
</script>

```