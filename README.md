# Module 16 Challenge - Amazon_Vine_Analysis

## Overview of the Project

### Purpose
The purpose of this project is to perform the ETL process on an Amazon Vine Review dataset held in an AWS RDS instance using PySpark. Our client, Jennifer, would like to perform an analysis to determine if there is any bias toward favorable reviews from Vine members in our dataset. 

## Results

### Deliverable 1 - Perform ETL on Amazon Product Reviews

- customers_table DataFrame

![customers_table](https://user-images.githubusercontent.com/103288980/192431224-c1e61785-8fcd-4bbc-9111-7733aa9cc872.PNG)

- products_table DataFrame

![products_table](https://user-images.githubusercontent.com/103288980/192431250-dd18515b-e9d7-40d5-a1fb-de096d516ac0.PNG)

- review_id_table DataFrame

![review_id_table](https://user-images.githubusercontent.com/103288980/192431265-cb7fab15-f26e-4897-8a04-4da44b473b13.PNG)

- vine_table DataFrame

![vine_table](https://user-images.githubusercontent.com/103288980/192431275-e1ccf08c-1f39-4b1c-ac14-48b07c6a3e38.PNG)

### Deliverable 2 - Determine Bias of Vine Reviews 

-How many Vine reviews and non-Vine reviews were there?
Our analysis determined there are 170 Vine reviews and 37,840 non-Vine reviews.

-How many Vine reviews were 5 stars? What percentage of Vine reviews were 5 stars? 
Our program determined there are 65 5-star Vine reviews and calculated this proportion to be 38.23% of all Vine reviews.

-How many non-Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
Our program determined there are 20,612 5-star non-Vine reviews and calculated this proportion to be 54.47% of all non-Vine reviews.

## Summary

### Recommendations
In summary, our analsyis shows there is no bias for 5-star reviews from paid Vine Program members. The analysis also determined there are more non-Vine 5-star reviews and a higher percentage of 5-star reviews in non-Vine reviews than in Vine reviews.
An additional analysis for future consideration would be to include the total_votes variable in our analysis. Determining the total_votes per star_rating for both Vine and non-Vine reviews may help us determine the significance of paid Vine reviews to customers' opinions.
