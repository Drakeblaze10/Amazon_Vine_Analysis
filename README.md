# Amazon_Vine_Analysis

## Overview of Analysis
Using PySpark on a video game dataset, I will perfrom the ETL process and connect to an AWS RDS instance and load it into pgAdmin. Then Use PySpark to determine if there is any bias toward reviews from vine members.

## Results
![Vine Reviews](https://github.com/Drakeblaze10/Amazon_Vine_Analysis/blob/main/Resources/paid%20vs%20unpaid.png)
How many Vine reviews and non-vine reviews are there?
- There was a total of 94 vine reviews and 40471 non-vine reviews.
How many Vine reviews were 5-stars? How many non-Vine reviews were 5 stars?
- There are 48 5-star reviews from Vine and 15663 non-Vine 5-star reviews.
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- 51% of vine reviews were 5-star, while 38% of non-vine reviews were 5-star

## Summary
There is a clear positivity bias when it comes to reviews from the Vine program. Non-Vine users will most likely be less inclined to give a 5-star review as most people tend to avoid perfection. I believe a great merit to this study is to compare these same filters to all star reviews. I would like to believe the majority of reviews for the non-vine reviews will fall under the 4-star rating.