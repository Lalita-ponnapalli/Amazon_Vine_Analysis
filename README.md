# Amazon_Vine_Analysis

## Overview of the analysis: 

The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.
In this project we access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. We picked one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. We used PySpark, SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. 
### Procedure (Extract-Transform-Load (ETL) Process)
Objective: Perform ETL process completely in the cloud and upload a Data Frame to an RDS instance by creating 4 Data Frames to match production-ready tables from  big Amazon customer review dataset.
Used Amazon reviews for us Toys.
Tables in PgAdmin
#### customers_table
![image](https://user-images.githubusercontent.com/100485119/174522408-cd968301-0a00-465a-aa30-e36b01ccbf81.png)

 
#### products_table1
 
![image](https://user-images.githubusercontent.com/100485119/174522418-3b51833b-f79f-442e-be5e-4bc5a73eed60.png)

#### review_id_table
 ![image](https://user-images.githubusercontent.com/100485119/174522427-23864caf-3052-44b3-aaff-fe7de41df494.png)

#### Vine Table
 
![image](https://user-images.githubusercontent.com/100485119/174522440-3a49e1c4-de2b-454a-8f61-08ed8e6d1263.png)

## Results:
#### Vine Review

#### vine reviews 1203
![image](https://user-images.githubusercontent.com/100485119/174522660-4d115d07-0f4b-49b4-b5b5-614c630f6104.png)

#### Non Vine reviews 58018
![image](https://user-images.githubusercontent.com/100485119/174522735-8eb55928-bb3f-48ae-b0e4-75cf4961655e.png)

#### vine review with 5 star are 410
![image](https://user-images.githubusercontent.com/100485119/174522794-74f29e8c-f863-4c3f-af6b-43b635e57aca.png)

#### Non Vine reviews with 5 star are 28043
![image](https://user-images.githubusercontent.com/100485119/174522805-019f9f9f-d847-43cd-b2de-46b3515cf18d.png)

#### Non vine review with 5 star percentage 98.56
![image](https://user-images.githubusercontent.com/100485119/174522839-90c467cb-9f98-4958-adb7-377510ff4f22.png)

#### Vine review with 5 star percentage 1.44

### Summary

As per research we get to know that Non vine review is higher the vine review. This information also tells us that it is not the best-selling item. For this case, I think the Vine Program is trustworthy. 
#### Further research
But as per my opinion this research is not enough. This should done on every product so we can know which product has the highest ratings which has less.








