Feature Importance Plot Format
===============

JSON
----

```json

option = {
    title: {
        text: 'Feature Importance',
        subtext: 'feature importance of ... dataset using permuation importance'
    },
    tooltip: {
        trigger: 'axis',
        axisPointer: {
            type: 'shadow'
        }
    },
    legend: {
        data: ['Permutaion Importance Score']
    },
    grid: {
        left: '3%',
        right: '4%',
        bottom: '3%',
        containLabel: true
    },
    xAxis: {
        type: 'value',
        boundaryGap: [0, 0.01]
    },
    yAxis: {
        type: 'category',
        data: ['longitude','latitude','housing_median_age','total_rooms','total_bedrooms','population']
    },
    series: [
        {
            name: 'Permutaion Importance Score',
            type: 'bar',
            data: [18203, 23489, 29034, 104970, 131744, 630230]
        }
    ]
};

```

That was my JSON code block.
