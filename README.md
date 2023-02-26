# Big-Data-ETL
During this project, I used the ETL skills I have learned in class to use the ETL process in the cloud to upload a DataFrame to an RDS instance. For Part 1, I extracted two Amazon customer reiew datasets, transformed each dataset into four DataFrames, and then loaded the DataFrames into an RDS instance.

# Part 1
First, I uploaded the part_one_starter_code.ipynb into Google Colab. Next, I explored the Amazon Reviews datasets and picked two datasets to perform ETL. Next, I renamed each file according to the dataset I used. Next, I extracted the data. First, I read in each dataset using the correct header and sep parameters. Then, I got the number of rows in the dataset. Next, I transformed the data. For each dataset, I used the schema.sql file located in the Resources folder to create the four DataFrames as follows. First, I created the "review_id_df" DataFrame with the appropriate columns and data types. Next, I created the "products_df" DataFrame that drops the duplicates in the "product_id" and "product_title" columns. Next, I created the "customers_df" DataFrame that groups the data on the "customer_id" by the number of times a customer reviewed a product. Next, I created the "vine_df" DataFrame that has the "review_id", "star_rating", "helpful_votes", "total_votes", and "vine" columns. Next, I loaded the data into an RDS instance. I exported each DataFrame into the RDS instance to create four tables for each dataset.

# Resources
This folder contains schema.sql.
