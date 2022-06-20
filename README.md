# Amazon_Vine_Analysis

## Overview of the analysis: 

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
In this project we access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. We picked one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. We used PySpark, SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. 
### Procedure (Extract-Transform-Load (ETL) Process)
Objective: Perform ETL process completely in the cloud and upload a Data Frame to an RDS instance by creating 4 Data Frames to match production-ready tables from  big Amazon customer review dataset.
Used Amazon reviews for us Toys.
Tables in PgAdmin
#### customers_table
 
#### products_table1
 

#### review_id_table
 
#### Vine Table
 

## Results:
#### Vine Review

vine reviews 1203
Non Vine reviews 58018
vine review with 5 star are 410
Non Vine reviews with 5 star are 28043
Non vine review with 5 star percentage 98.56
Vine review with 5 star percentage 1.44
### Summary

As per research we get to know that Non vine review is higher the vine review. This information also tells us that it is not the best-selling item. For this case, I think the Vine Program is trustworthy. 
#### Further research
But as per my opinion this research is not enough. This should done on every product so we can know which product has the highest ratings which has less.








