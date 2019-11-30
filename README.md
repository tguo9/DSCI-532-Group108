# DSCI-532-Group108

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Ftguo9%2Ficon_test%2Fmaster%2Ftest.json)](https://plot.ly/dash/)

Team members: Frank Lu, Derek Kruszewski, Tao Guo  

## Description of APP  
This APP is intended to show the historical crime data in a geo-temporal form.  To achieve this, it will display a choropleth of City of Vancouver for showing neighbourhoods and a line chart for showing the relationship between crime count and time.   This APP will be interactive and allows its users to specify the neighbourhood, crime type, and time scale to gain more understanding of how crimes are correlated to the neighbourhoods and time.
  
On the choropleth, the number of crimes in different neighbourhoods is colour-coded so that users can easily relate the count of a crime type to its relative location in Vancouver.  A dropdown list will be added for choosing the crime type.  There will also be a slider bar for changing the year range of the crime data, in case some users might be interested in a more recent crime data.  
  
In the line chart, we intend to show how the count of crimes in a neighbourhood varies with time.  So, there will be two dropdown lists accompanying the line chart: one for selecting the neighbourhood, and the other for selecting the time scale.  This way, the users can easily see the specified neighbourhood’s criminal trend in terms of the time, date, month or year. 

## Functionalities
This ‘Vancouver Crime Stats’ app is an app combined with multiple dropdowns and two slider bars. Those controllers can let the user filter out different crime types and time ranges. The graph on the left allows users to zoom in to the neighbourhood and show the time statistics on different time scales.

## Documentation
- Crime Type: A drop down box that let use select the crime types happened from 2003 to 2018. Default crime is all crime types combined together.
- Years to Include: From 2003 to 2018. Select the year ranges. Default year range is from 2003 to 2018.
- Neighbourhood: Neighbourhoods in Vancouver. Default is all neighbourhoods.
- Time Scale: Select from year, month, day of the week and time. Default time scale is year.
- The Crime Index: A threshold that change the colour across all neighbourhoods in Vancouver. Default threshold is 1.

![](img/App-Deployed.png)
