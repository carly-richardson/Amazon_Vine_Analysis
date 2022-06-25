# Amazon Vine Analysis
## Overview
This is an analysis of Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program allows companies to pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review. I used PySpark and SQL to determine if there is any bias toward favorable reviews from Vine members in my dataset.

This analysis consists of two technical analyses:
  1. Perform ETL on Amazon Product Reviews
  2. Determine Bias of Vine Reviews

## Results
  - In my dataset of US Amazon watch reviews, there were 1,747 reviews from Vine members and 958,932 reviews from non-Vine members.
  - There were 605 five-star Vine reviews and 570,888 non-Vine reviews.
  - 34.63% of Vine reviews were five-stars. 59.53% of no-Vine reviews were five-stars.

       ![Screen Shot 2022-06-25 at 1 41 01 PM](https://user-images.githubusercontent.com/100643519/175786494-f12cda59-9162-4a3f-bd2f-51a16de8cc1b.png)


## Summary
In my Amazon dataset, there was not any positivity bias for reviews in the Vine program. The percentage of five-star reviews from non-Vine members was higher than the perecentage of five-star reviews from Vine members, 59.53% and 34.63% respectively. I could perform an additional NPL analysis of the text from the review body from Vine reviews and non-Vine reviews to further support that conclusion.
