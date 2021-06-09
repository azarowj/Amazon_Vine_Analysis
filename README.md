# Amazon_Vine_Analysis

## Overview of the Analysis

Amazon has a paid program called Amazon Vine. This program allows manufacturers and publishers to receive reviews for their products. Companies pay a fee to Amazon and provide their products to Amazon Vine members, who in turn are then required to publish a review. In this project, we will use a dataset containing reviews for a specific product. We then used PySpark to perform the ETL process. We then used Pandas to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Results

- There were 261 Vine reviews
- There were 24,040 non-Vine reviews
- There were 106 5-star Vine reviews
- There were 10,899 5-star non-Vine reviews
- Approximately 41% of Vine reviews were 5 stars
- Approximately 45% of non-Vine reviews were 5 stars

## Summary
This particular dataset does not show any positivity bias for reviews in the Vine program. The percentage of 5-star reviews from people in the Vine program is actually 4% less than that of people not in the Vine program. If positivity bias existed, we would expect to see the percentage of 5-star ratings be higher from people in the Vine program. I would also want to look into the average ratings, from people in the Vine program versus people not in the Vine program. Another indicator of positivity bias could be an overall higher average rating. I would be curious to see if there were any 1-star reviews from people in the Vine program in the filtered dataset.
