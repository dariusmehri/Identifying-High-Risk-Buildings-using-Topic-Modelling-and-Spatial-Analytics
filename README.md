# Topic Modelling of High Risk Buildings

The objective of this project is to identify gas-related high risk buildings in New York City. A building is determined "high" risk if there is a high likelihood of harm to New York City residents,  due to poor workmanship or illegal activity. 

The project had four steps:

1. Analysis of text data using topic modelling and identifying key works that indicate high risk.

2. Creating a risk scale for each building.

3. Creating list a high risk buildings to be inspected.

4. Creating a spatial dashboard using Tableau.

Structural topic modelling package in R was used for natural language processing analysis and geocoding,  python was used to clean and code the data, Tableau was used to visualize data.

## Results

Text data from Con Edison visits were analyzed, topic modelling automatically generates topics from the text. The topics can be broadly categorized as incidents related to boilers, customer complaints of service shut off, gas leaks, gas meter issues, illegal activity and service shut off, failure of integrity tests and unsafe piping.

## Report
https://www1.nyc.gov/assets/buildings/pdf/gas_utility_analytics_November2020.pdf


## Spatial Dashboard
The dashboard included a map of incidents (high risk red, low risk yellow), 3D satallite image of building and menus to filter the data. A user can click on an incident of interest on the map and an automatic satellite image of the building is produced. Notes of the incident are also shown when a user hovers the mouse over the incident. Below is an image of the dashboard:

![alt tag](https://cloud.githubusercontent.com/assets/11237613/17219083/068dba4e-54b8-11e6-9193-9e38f8814f8d.png)
