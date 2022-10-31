# ADA: Dram Shop PCA

In this assignment we use PCA to investigate purchasing habits of Dram Shop customers. Since the Dram Shop has so many items, we need dimensionality reduction to help us understand the patterns of consumption. This assignment does not start you with any code, so you'll need to create a Jupyter notebook to hold your analysis. 


Here are the steps you'll undertake: 

1. Write a query in GBQ that returns the values of `beverage` (from the table `item_lookup`) with the top 1000 gross sales totals. 
1. Building off the previous query, write a query that returns three columns: the customer ID, the beverage, and the total sales. Only return beverages from the top 1000 beverages. 
1. Using the pandas function `pivot`, pivot the data into a "wide" format with customer IDs as the rows and beverages as the items. You can see an example [here](https://stackoverflow.com/questions/22798934/pandas-long-to-wide-reshape-by-two-variables). 
1. Using the `PCA` function from `sklearn.decomposition`, perform a PCA on this data set. Plot the amount of explained variation in the first 20 components.
1. For each of the first 6 components, print the items with the 15 largest loadings in absolute value. 
1. Write up a brief interpretation on what aspect of the data that component seems to be capturing.

