# Seattle City Leading Top Five Causes of Death From 2007 to 2014

## Introduction

This project is developed by bm19 for CS498DV Data visualization course project. By using [D3.js](https://d3js.org), top five leading causes of death in Seattle City from 2012 to 2019 are presented. An intro-video can be found [here].

## Project URL
A demo of the end result can be seen here:
https://bm19.github.io/dataviz-project/.

The code can be found here:
https://github.com/bm19/dataviz-project


## Data Source

The data source of this project is from [Seattle City Leading Causes of Death](https://www.doh.wa.gov/DataandStatisticalReports/HealthStatistics/Death), and we pre-process the data by selecting top five causes of death and related features.


## Descriptions of Visualization and Interactions

This visualization mainly consists of two parts. 1) The line chart in the left panel shows the trend of death number vary of each disease from 2007 to 2014, while X axis presents years and Y axis presents number of deaths. The names of the diseases are in the bottom of the line chart with different colors, and the color of the line indicates which disease it associates with. 2) The grouped bar chart in the right panel shows the distribution of death number over gender and race in selected year for selected disease/all. This bar chart also includes a selection bar on the top for year selection. 

In the left panel, by clicking/unclicking the disease name, user can select/unselect the disease he/she want to be updated on the right panel. If no disease is selected, the right panel shows the distribution of total death number over gender and race in selected year. 

In the right panel, by dragging slider on the selection bar, the grouped bar chart below will be updated to present the number of deaths in each race and gender in selected year. Hover on a bar, a tooltip will appear to show detailed information of this bar including year, death number, race and gender.

Figure 1.
![image](https://github.com/bm19/dataviz-project/blob/master/photos/Untitled-3.png)

## Answered questions and discussions
From 2012 to 2019, How does the total death number or death rate vary over time?

As shown in Fig. 1, The death number of heart disease decreased, while the death number of All other cause increased. There is not much volatility for diabetes, flu and malignant neoplasms.

In each year, how is the death number distributed over races and gender?

As shown in Fig. 2, for the death number, white > Africa american > hispanic > asian, and this pattern is kept in different year. Because we lack of the total population distribution over race and gender，we can not make conclusion that whether a disease have a higher/lower death rate for a particular race.

Figure 2.
![image](https://github.com/bm19/dataviz-project/blob/master/photos/Untitled-2.png)

Is there any correlation between gender or races and diseases?

As shown in Fig. 3, we can notice that for diabetes a significate increase of death number of Africa american women than it in Africa american men，whilc compare with the pattern in other race. That may indicate a correlation between Africa american women and diabetes.

Figure 3.
![image](https://github.com/bm19/dataviz-project/blob/master/photos/Untitled-1.png)

