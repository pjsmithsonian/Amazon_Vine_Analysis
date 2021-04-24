# Amazon_Vine_Analysis

## Overview
We are analyzing Amazon reviews written by members of the Vine program. In this analysis we are attempting to locate any bias towards 5-star reviews in these paid reviews.

## Results
Narrowing our total dataset down to those reviews with more than twenty votes, having 50% helpful votes, we were ready to do our analysis.

![starting_data](/Resources/helpful_df.PNG)

### Findings

We found the following:
 - Total number of reviews: 65581
 - Total number of paid reviews: 613
 - Total number of unpaid reviews: 64968
 - Number of paid 5-star reviews: 222
 - Number of unpaid 5-star reviews: 30543
 - Percentage of paid 5-star reviews: 0.72%
 - Percentage of unpaid 5-star reviews: 99.28%

## Summary
After our analysis, based on the low percentage, .72%, of 5-star reviews from Vine members, there does not appear to be any bias towards 5-star reviews for the paid members. To look further into this, we may want to perform analysis of where the majority of Vine reviews fall on the rating scale. We may not be incentivizing these Vine members to give falsely high ratings, but this further analysis would help flesh out any bias that may exist otherwise.