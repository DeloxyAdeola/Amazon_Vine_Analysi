# Amazon_Vine_Analysis
This project purpose is basically working with big data and how ETL processes can be performed in getting accurate analysis using Python and the PySpark ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin.I chose a dataset from the AMazon review dataset(amazon_reviews_us_Jewelry_v1_00.tsv.gz).The essential  analysis is to determine if there is any bias toward favorable reviews from Vine members and non vine members in the dataset. 

RESULTS
HOW MANY VINE REVIEWS AND NONE -VINE REVIEWS WERE THERE?

 [alt text](https://github.com/DeloxyAdeola/Amazon_Vine_Analysi/blob/main/fig/fig%201.png)
 
 [alt text](https://github.com/DeloxyAdeola/Amazon_Vine_Analysi/blob/main/fig/fig%202.png)

Total number of Vine reviews:21

Total number of non-vine reviews: 7689

Total number of Vine reviews that were 5 stars were 11

Total number of 5-star vine reviews: 1650

Total number of 5-star vine reviews with 20 or more votes: 11

Total number of 5-star vine reviews with 20 or more votes and 50% or more helpful votes: 21

Percentage of 5-star paid reviews: 0.5238095238095238

Percentage of 5-star unpaid reviews: 0.51931330472103

[alt text](https://github.com/DeloxyAdeola/Amazon_Vine_Analysi/blob/main/fig/fig%203.png)

[alt text](https://github.com/DeloxyAdeola/Amazon_Vine_Analysi/blob/main/fig/fig%204.png)

Summary

Based on the results of the analysis we can tell that the total number of  non vine reviews are more than the the total number of vine review of which we can conclude that those numbers are honest feeback from the product used, unlike the vine reviews of which majority might not have use the product being that they did not purchase the product because they have need for it but for the sake of reviews by amazon. For the percentage of 5-star reviews from Vine and non-Vine reviews, there may not be a large positivity bias for reviews in the Vine program. 

For future and accurate analysis, it would be more precise if we can analyze based on different rating to be able to ascertain the product value on each category of view. moreso, there should be  and accurate review why the none vines members tend to give more reviews that the vine reviews, with these analyses we can actually conclude if the reviews are bias or not. Also for an unbiased positivity, it will be better if we can come up with a strategy that would encouraged non vine members to review products that are purchased.
