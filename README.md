# seoul_bike_regression

This repository contains the work conducted with a classmate (Stephen Somsack) for the Data Mining course at the University of the West of Scotland (UWS).

During this project, we only used R as the programming language.

## Presentation of the dataset

The dataset is public and comes from the UCI Machine Learning Repository (https://archive.ics.uci.edu/ml/datasets/Seoul+Bike+Sharing+Demand#)

The dataset contains a count of public bikes rented hourly in Seoul Bike sharing System with the corresponding weather data and holidays information. 

It is a multivariate dataset with a total number of 14 attributes.

|  Feature | Type |
|---|---|
| ***Rented bike count (target variable)*** | integer |
| Date | date |
| Hour (hour of the day) | integer |
| Dew point temperature (Celsius) | float |
| Solar radiation (MJ/m2)  | float |
| Rainfall (mm) | float |
| Snowfall (cm) | float |
| Humidity (%) | float |
| Visibility (10m) | float
| Temperature (in Celsius) | float |
| Seasons | categorical |
| Functional Day (Non Functional hours/ Functional Hours) | Boolean |
| Holiday | Boolean |


## Description of the different files

* Report: summary of the work (brief literature review, results from the EDA, the different models and their results)
* seoul_notebook.nb.html: Exploratory Data Analysis
* seoul_regression.html: Regression models
