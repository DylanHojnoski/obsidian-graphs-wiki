# Chart

Chart creates different types of charts it takes in an array of data and in the att you need to set chartStyle which can be:
* bar
* fit
* line
* pie
* points
* radar
* spline

## Bar

````yaml
```graph
bounds: [-10, 10, 10, -10]
elements: [
	{type: chart, def: [1,2,3,4], att: {chartStyle: bar}}
]
```
````

![chartBar](imgs/Chart-graph-1.png)

## Fit

````yaml
```graph
bounds: [-10,  10,  10,  -10]
elements: [
	{type: chart, def: [1,2,3,4], att: {chartStyle: fit}}
]
```
````

![chartFit](imgs/Chart-graph-2.png)

## Line

````yaml
```graph
bounds: [-10, 10, 10, -10]
elements: [
	{type: chart, def: [1,2,3,4], att: {chartStyle: line}}
]
```
````

![chartLine](imgs/Chart-graph-3.png)

## Pie

````yaml
```graph
bounds: [-10,10,10,-10]
elements: [
	{type: chart, def: [1,2,3,4], att: {chartStyle: pie}}
]
```
````

![chartPie](imgs/Chart-graph-4.png)

## Radar

Radar needs a paramArray.

````yaml
```graph
bounds: [-10, 10, 10, -10]
elements: [
	{type: chart, def: [[1,2,3], [4,3,2], [-5,-6,0], [-1,5,1]], att: {chartStyle: radar, paramArray: [x, y, z]}}
]
```
````

![chartRadar](imgs/Chart-graph-6.png)

## Spline

Takes an array of x coordinates and an array of y coordinates

````yaml
```graph
bounds: [-10, 10, 10, -10]
elements: [
	{type: chart, def: [[1,2,3], [4,3,2]], att: {chartStyle: spline}}
]
```
````

![chartSpline](imgs/Chart-graph-7.png)

