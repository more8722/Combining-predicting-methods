# Combining-predicting-methods
This is multi tasks project, include store format for current stores, store format for new stores, forecasting exist, new stores sales.
## Task 1: Store Format for Existing Stores
Your company currently has 85 grocery stores and is planning to open 10 new stores at the beginning of the year. Currently, all stores use the same store format for selling their products. Up until now, the company has treated all stores similarly, shipping the same amount of product to each store. This is beginning to cause problems as stores are suffering from product surpluses in some product categories and shortages in others. You've been asked to provide analytical support to make decisions about store formats and inventory planning.  
## Task 1: Determining Store Format
To remedy the product surplus and shortages, the company wants to introduce different store formats. Each store format will have a different product selection in order to better match local demand. The actual building sizes will not change, just the product selection and internal layouts. The terms "formats" and "segments" will be used interchangeably throughout this project. You’ve been asked to:

Determine the optimal number of store formats based on sales data.
Sum sales data by StoreID and Year
Use percentage sales per category per store for clustering (category sales as a percentage of total store sales).
Use only 2015 sales data.
Use a K-means clustering model.
Segment the 85 current stores into the different store formats.
Use the StoreSalesData.csv and StoreInformation.csv files.
