# Amazon_Vine_Analysis

## Overview of the Analysis

Amazon has a paid program called Amazon Vine. This program allows manufacturers and publishers to receive reviews for their products. Companies pay a fee to Amazon and provide their products to Amazon Vine members, who in turn are then required to publish a review. In this project, we will use a dataset containing reviews for a specific product. We then used PySpark to perform the ETL process. We then used Pandas to determine if there is any bias toward favorable reviews from Vine members in the dataset.

## Results

- There were 0 Vine reviews
- There were 403,807 non-Vine reviews
- Since there were 0 Vine reviews, 0 Vine reviews were 5 stars
- There were 242,889 5-star non-Vine reviews
- Since there were 0 Vine reviews, 0% were 5 stars
- Approximately 60% of non-Vine reviews were 5 stars

## Summary
This particular dataset does not show any positivity bias for reviews in the Vine program. After filtering our data, our data frame contained 0 reviews from the Vine program. I went back to the original dataframe and filtered it for reviews in the Vine program. The original dataset only contained 2 reviews from the Vine program, which can be seen [here](https://github.com/azarowj/Amazon_Vine_Analysis/blob/main/VineProgram.png). If I wanted to look further into the possibility of positivity bias in the Vine program, I would need to do this analysis over with a different dataset.
