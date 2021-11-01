# Comparative Analysis
Comparative analysis is a method to compare two or more entities/datasets. The data to enable this is prepared via [informaion mappaing](https://github.com/The-Data-for-Children-Collaborative/noral-tech-research/tree/main/information-mapping) but it needs a tool(s) to outlet the comparision of the datasets. 

While most of the analysis can be aided by the tools analysed [here](https://github.com/The-Data-for-Children-Collaborative/noral-tech-research/tree/main/data-analysis), effectively communicating the information extracted from the data demands a custom toolkit with customizable visual/user flows. 

To enable this, following tools are considered

1. D3.js
2. Apache ECharts
3. Chart.js

## D3.js
D3.js is a JavaScript library for manipulating documents based on data. D3 helps bring data to life using HTML, SVG, and CSS. D3’s emphasis on web standards gives you the full capabilities of modern browsers without tying yourself to a proprietary framework, combining powerful visualization components and a data-driven approach to DOM manipulation. [ref](https://d3js.org/)

## Apache ECharts
Apache Echarts is a visualization library built with easy-to-use, rich built-in interactions, and high performance as goals. It enables high expandability and performance by employing performant graphics and streaming arhcitecture. 

## Chart.js
Chart.js describes itself as "Simple yet flexible JavaScript charting for designers & developers". It enables data visualization using 8 charttypes which are performant, reposnsive and stackable.

While all the above mentioned tools can enable most of the comparative analysis in hand, we selected Apache Echarts for its ease of use and scalable setup.

By creating extendable visualization plugins using Apache Echarts in conjunction with resource and page models [explained here](https://github.com/The-Data-for-Children-Collaborative/noral-tech-research/tree/main/system-architecture), most of the userflows and visualization flows can be created with minimal development effort.  