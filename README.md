## Home_Sales
# Overview of the Analysis
The purpose of this analysis was to leverage PySpark and Spark SQL to analyze home sales data.

# Data Description:
The dataset contains information for over 33,000 homes sold between 2019-2022. The original dataset can be found here.
The dataset has 11 columns including: id, date, date_built, price, bedrooms, bathrooms, sqft_living, sqft_lot, floors, waterfront, and view rating.
# Approach:
Create a Spark Session and read in the CSV file into a dataframe
Preview the first 20 rows of the dataframe
Create temporary views of the data
Run queries on cached and uncached data and compare the run times
Partion the data and leverage parquet formatted data
Run queries in Spark to answer the questions below
