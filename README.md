# Amazon_Vine_Analysis
Using Pyspark to perform ETL and connect to an AWS RDS instance


## Overview

In this project, we’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. We’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, we’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, we’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

##Results

Using our knowledge of the cloud ETL process, well’ll create an AWS RDS database with tables in pgAdmin, pick a dataset from the Amazon Review datasets Links to an external site., and extract the dataset into a DataFrame. We'll transform the DataFrame into four separate DataFrames that match the table schema in pgAdmin. Then, we'll upload the transformed data into the appropriate tables and run queries in pgAdmin to confirm that the data has been uploaded.


- First, we create a new database in our Amazon RDS Server, and then we run queries to create tables for our new databse in pgAdmin

<img width="1076" alt="Screenshot 2023-01-23 at 1 13 09 AM" src="https://user-images.githubusercontent.com/47859209/213976204-5050f1ea-6f93-4952-a356-59c5d230f86e.png">

- Next, we extract our dataset for review and then create a new Dataframe
<img width="1337" alt="Screenshot 2023-01-23 at 1 16 11 AM" src="https://user-images.githubusercontent.com/47859209/213976538-bd500d5a-f9c8-45f6-94af-103973480c60.png">


- Using our knowledge of PySpark, Pandas, or SQL, we’ll determine if there is any bias towards reviews that were written as part of the Vine program. For this analysis, we'll determine if having a paid Vine review makes a difference in the percentage of 5-star reviews.

<img width="1356" alt="Screenshot 2023-01-23 at 1 18 26 AM" src="https://user-images.githubusercontent.com/47859209/213976830-6938407e-fddf-4849-9616-30149fe443cd.png">

