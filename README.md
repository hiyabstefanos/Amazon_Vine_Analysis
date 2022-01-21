# Amazon_Vine_Analysis

Extract, transform, and load a dataset using PySpark, pgAdmin, and an AWS RDS instance.

Review Dataset (https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt)
Books Dataset (https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Books_v1_02.tsv.gz)


## Overview of the analysis: 

As a startup with a catalog of products that are ready to hit the market, it is crutial to understand which programs are benifiting the buisness and which are not. In order to optimize marketing efforts, we analyzed if the paid Amazon Vine program - a program which provides consumers with to recieve products for review - is worth the investment by looking at a dataset of reviewed books.


## Results: 

Using bulleted lists and images of DataFrames as support, address the following questions:
<img width="515" alt="Num  of Reviews" src="https://user-images.githubusercontent.com/89358080/150485246-45301c73-e524-48f5-83e2-a34e67374e6c.png">
- There were no Vine reviews for books, but there were 403807 non Vine reviews

<img width="588" alt="5 stars total" src="https://user-images.githubusercontent.com/89358080/150485410-258aeafa-05c9-4ce8-9205-c6ae6d0df284.png">
- The total number of 5 star reviews was 242889

<img width="844" alt="5 stars per" src="https://user-images.githubusercontent.com/89358080/150485655-cd4495ea-0d57-4940-8674-ea9b15cd4f89.png">
- There were 0% Vine reviews, but 60% of non-Vine reviews were 5 stars

## Summary: 

After analyzing the number of book reviews affiliated with Vine and comparing this to the number of reviews that were not affiliated with Vine, we find that there is not benifit to investing in this platform. There is not enough data to support if Amazon Vine positively or negatively affects reviews. But overal those who are engaged in the platform are generally leaving positive reviews. No book reviews were associated with Vine, but out of the reviews left (non-Vine) 60% were five star. We can dive deeper into this data to determine how many 4, 3, 2, and 1 star reviews were written.
