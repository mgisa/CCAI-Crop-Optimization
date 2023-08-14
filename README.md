# Prosed Title Project: Statistical Ensemble Learning Machine for Cassava Yield Optimization in Nigeria

## Introduction and Background

## Methodology

 ### Data Source and Description

 The data to be used in this project have been sourced from different sources for different purposes but keeping in our mind to filter the region of interest(Nigeria) and period of the year. The data is time-series with the frequency of years mostly ranging from 1961 to 2021.

The data sources are as follows:
- Food and Agriculture Organization of the United Nations
  We sourced the agricultural-related data such as inputs and yield (the ratio between production and area harvested)
- The World Bank (Climate Change Knowledge Portal for Development practitioners and policymakers).
  We source the periodic climate and weather observations (yearly average precipitation, and mean temperature) and Reanalysis relative humidity.

Note: Since the data files are row data they need to be cleaned and tidied to facilitate modeling
- We need to select the interested variables from the weather data files (removing the regional data points and keeping only data on the country level)
-  From the crop yield data file which is long format should be put in wide format to have `yield`, `production`, and `area_harvert` columns
-  From inputs data files, convert it also in wide format to have the columns like `insecticides`, `pesticides`,...

After cleaning and preparing the data we will be able to head to the modeling where we will be selecting different ML algorithms to be used (either 10 or above) then we will ensemble them to have the super learner ML model for cassava prediction in Nigeria.
