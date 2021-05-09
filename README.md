# SalesAnalysis
Data Cleaning and Analysis using Python Pandas and Matplotlib

# Background

You are provided with 12 months worth of sales data. The data contains hundreds of thousands of electronics store purchases broken down by month, product type, cost, purchase address, etc. My job is to perform data cleaning and carry out some analysis to answer some business questions. 

Here is a sneak peak into how I approached this task:

1. There are 12 '.csv' files each containing monthly sales data. I have combined all these 12 files into one csv file.
2. Data cleaning:
      * Drop NaN values from DataFrame
      * Removing rows based on a condition
      * Change the type of columns (to_numeric, to_datetime, astype)
3. Data exploration:
      * What was the best month for sales? How much was earned that month?
      * What city sold the most product?
      * What time should we display advertisemens to maximize the likelihood of customer’s buying product?
      * What products are most often sold together?
      * What product sold the most? Why do you think it sold the most?

# References

The data has been acquired from Keith Galli:

https://github.com/KeithGalli/Pandas-Data-Science-Tasks

***Stack Overflow***

https://stackoverflow.com/questions/43348194/pandas-select-rows-if-id-appear-several-time
https://stackoverflow.com/questions/27298178/concatenate-strings-from-several-rows-using-pandas-groupby
https://stackoverflow.com/questions/52195887/counting-unique-pairs-of-numbers-into-a-python-dictionary
https://stackoverflow.com/questions/14762181/adding-a-y-axis-label-to-secondary-y-axis-in-matplotlib
