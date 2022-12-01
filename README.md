# Web-Design-Challenge


## Overview 

In this repository, the user analyzed data from over 500 cities across the world to answer the question, "What is the weather like as we approach the equator?" Using the Open Weather Map API and Google Places API the results to this question are shown below in detail. Matplotlib and gmaps were used to visualize the results of this data. 

The visualizations were then used to create a website that allows the user to seamlessly move between each graph and encounter a description below it. 

The website consists of the following pages:

###
Landing page: This page explains the purpose of the project as well as a link to each of the four visualiztion pages. 

Comparison page: This page compares each of the four visualizations(cloudiness, temperature, humidity, and wind speed).

Data page: This page displays a responsive table of each city that was analyzed and the data within it. 

Four visualization pages: Each visualization page contains a descriptive title and heading and compares latitude to one of the four factors to  (cloudiness, temperature, humidity, and wind speed). 

## Analysis

Matplotlib was used to visualize the results of this data and uncover trends between latitude of cities and various variables such as maximum temperature (F), cloudiness, humidity percentage, and wind speed (mph). There are multiple scatter plots within WeatherPy that portray the relationships among latitude and previously stated variables, some including linear regression models to determine if there is a predictive value among the two variables.

## Observations 

There is a negative trend between maximum temperature and increasing latitude. The inverse is true for maximum temperature and decreasing latitude. This is an obvious trend as the farther away from the equator we go, the temperature continues to decrease and vice versa.

Based on the data present in thie repository, it appears that humidity percentage in the northern and southern hemisphere have little to no correlation. There are significantly less cities analyzed in the southern hemisphere within this dataset which could impact the overall results.

Similarly, there appears to be no trend between the cloudiness and relationship between city latitude in both the northern and southern hemispheres.
