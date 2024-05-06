# Big-Data-ETL
## Amazon review ETL
Extract, Transform and Load Amazon Review Data Using Spark

## Objectives
### Step 1 - Extract the Data
- Explore the Amazon Reviews datasets and pick two datasets to perform ETL
- Read in each dataset using the correct header and sep parameters

![image](https://github.com/antara2022/Big-Data-ETL/assets/112270155/d1bd7778-b1e6-416d-809e-dfc5f9ddef55)

- Get the number of rows in the dataset
### Step 2 - Transform the Data
- Create the "review_id_df" DataFrame with the appropriate columns and data types

![image](https://github.com/antara2022/Big-Data-ETL/assets/112270155/da930deb-3075-4057-8707-56b3003f0658)

- Create the "products_df" DataFrame that drops the duplicates in the "product_id" and "product_title" columns

![image](https://github.com/antara2022/Big-Data-ETL/assets/112270155/932d8152-e51d-4278-a388-b770246321ec)

- Create the "customers_df" DataFrame that groups the data on the "customer_id" by the number of times a customer reviewed a product

![image](https://github.com/antara2022/Big-Data-ETL/assets/112270155/3520bf3c-5993-4c01-a5bf-8830b5ba7b41)

- Create the "vine_df" DataFrame that has the "review_id", "star_rating", "helpful_votes", "total_votes", and "vine" columns

![image](https://github.com/antara2022/Big-Data-ETL/assets/112270155/8609a912-e80b-4eeb-9fa2-6314763e12ab)

### Step 3 - Load the Data
- Export each DataFrame into the RDS instance to create four tables for each dataset

Contact: antara.choudhury3000@gmail.com
