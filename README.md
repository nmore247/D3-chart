# D3-chart


![image](https://user-images.githubusercontent.com/90889565/133732572-3f66b902-6812-4767-8f82-50eb919b884e.png)


var line = d3.line()
  .x(d => this.xScale(d.date))
  .y(d => this.yScale(d.price));
