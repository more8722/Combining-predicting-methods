# Combining-predicting-methods
This is multi tasks project, include store format for current stores, store format for new stores, forecasting exist, new stores sales.
### Task 1: Store Format for Existing Stores
Your company currently has 85 grocery stores and is planning to open 10 new stores at the beginning of the year. Currently, all stores use the same store format for selling their products. Up until now, the company has treated all stores similarly, shipping the same amount of product to each store. This is beginning to cause problems as stores are suffering from product surpluses in some product categories and shortages in others. You've been asked to provide analytical support to make decisions about store formats and inventory planning.  
### Task 1: Determining Store Format
To remedy the product surplus and shortages, the company wants to introduce different store formats. Each store format will have a different product selection in order to better match local demand. The actual building sizes will not change, just the product selection and internal layouts. The terms "formats" and "segments" will be used interchangeably throughout this project. You’ve been asked to:

Determine the optimal number of store formats based on sales data.
Sum sales data by StoreID and Year
Use percentage sales per category per store for clustering (category sales as a percentage of total store sales).
Use only 2015 sales data.
Use a K-means clustering model.
Segment the 85 current stores into the different store formats.
Use the StoreSalesData.csv and StoreInformation.csv files.
### Task 2: Store Format for New Stores
The grocery store chain has 10 new stores opening up at the beginning of the year. The company wants to determine which store format each of the new stores should have. However, we don’t have sales data for these new stores yet, so we’ll have to determine the format using each of the new store’s demographic data.    
### Task 2: Determine the Store Format for New Stores
You’ve been asked to:

Develop a model that predicts which segment a store falls into based on the demographic and socioeconomic characteristics of the population that resides in the area around each new store.
Use a 20% validation sample with Random Seed = 3 when creating samples with which to compare the accuracy of the models. Make sure to compare a decision tree, forest, and boosted model.
Use the model to predict the best store format for each of the 10 new stores.
Use the StoreDemographicData.csv file, which contains the information for the area around each store.
Note: In a real world scenario, you could use PCA to reduce the number of predictor variables. However, there is no need to do so in this project. You can leave all predictor variables in the model.  
### Task 3: Forecasting
Fresh produce has a short life span, and due to increasing costs, the company wants to have an accurate monthly sales forecast.


Task 3: Forecasting Produce Sales
You’ve been asked to prepare a monthly forecast for produce sales for the full year of 2016 for both existing and new stores. To do so, follow the steps below.
