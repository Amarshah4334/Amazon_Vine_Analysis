# Amazon_Vine_Analysis
ETL- Big Data, Google Colab, Postgres, AWS
# Analysis Overview

The analysis uses PySpark to perform the ETL process to extract the data, transform , connect to an AWS/ RDS , load the data into pgAdmin. 
We focused on the US reviews for furniture

# Background
Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, you’ll have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. You’ll need to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, you’ll use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your dataset. Then, you’ll write a summary of the analysis for Jennifer to submit to the SellBy stakeholders.

# Resources
Data Source: AWS
Software: Google Colab, PostgreSQL, pgAdmin, AWS
# Results
# Total number of reviews
 ![image](https://user-images.githubusercontent.com/96351897/165031850-29291fdb-95d5-4a04-98d4-9d3f6de7b865.png)



# Total number of 5-star reviews
![image](https://user-images.githubusercontent.com/96351897/165032038-805f982e-6f16-4d04-8e66-d234a68a1bc3.png)


![image](https://user-images.githubusercontent.com/96351897/165032059-0a0fb01b-96d5-4c81-b58d-fb06c5b63062.png)



# Types of reviews
## Vine reviews
![image](https://user-images.githubusercontent.com/96351897/165031953-288b0ecf-2461-4e6f-809d-af0dbaa45f8f.png)



## Non-Vine reviews

![image](https://user-images.githubusercontent.com/96351897/165031976-c3df1501-a166-472d-a926-745115f73829.png)


# Summary

The majority of reviews for Furniture product are 99.6% are Non-Vine.
 5 Star reviews: 99.7% of all 5-star reviews are non-Vine.
