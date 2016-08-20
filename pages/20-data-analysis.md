---
layout: page
title: Data Analysis
---
 
After finalizing your hypothesis, determine which data you need to collect and analyze test your hypothesis. 

### Variable definition and data 

Determine which variables you want to measure:

* Brainstorm a list metrics which enable you to prove/disprove your hypothesis
* Research academic papers and note which metrics they collected
* Narrow variable to ones which are directly related to proving the hypothesis, and can be consistently measured
* Determine any derived metrics (e.g. efficiency, longevity, etc..)

Create a plan for data collection which includes:

* Detailing the procedures
* Callibration of measurement device
* Ensuring quality control of measurement procedures
* Ensuring consistent units of measure 
	
### Create a plan for statistical analysis
	
	* Min, max, average
	* Statistical significance
		
### Determine best way to visualize your data

|	   |Col2   |Col3   |Col4   |Col5   |
|---|---|---|---|---|
|Row1   |12   |15 |20   |12   |
|Row2   |15   |11 |34   |55   |
|Row3   |16   |1  |12   |78   |

### Google Chart Example
<script type="text/javascript" src="https://www.gstatic.com/charts/loader.js"></script>
<script type="text/javascript">
      google.charts.load('current', {'packages':['corechart']});
      google.charts.setOnLoadCallback(drawChart);
      function drawChart() {
        var data = google.visualization.arrayToDataTable([
          ['Time Series', 'Var 1'],
          ['1',  100],
          ['2',  1200],
          ['3',  1000],
          ['4',  1030],
		  ['5',  500],
		  ['6',  500],
		  ['7',  100]
        ]);

        var options = {
          title: 'My Analysis',
          hAxis: {title: 'Time',  titleTextStyle: {color: '#333'}},
          vAxis: {minValue: 0}
        };

        var chart = new google.visualization.AreaChart(document.getElementById('chart_div'));
        chart.draw(data, options);
      }
    </script>
	
<div id="chart_div" style="width: 800px; height: 500px;align: left;"></div>
