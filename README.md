# Amazon Vine Analysis

## Overview of the Analysis
Demonstrating the ETL process by extracting, transforming, and connecting to AWS RDS. We then loaded the data into pgAdmin. We then determined if there was a bias towards favorable reviews from Vine participants.

## Results

* How many reviews were there?

  * Total Number of Reviews: 26,987

* How many of each type of review were 5 stars?

  * Five Star Vine Reviews: 0
  * Five Star Non-Vine Reviews: 14,475

* What percentage of the reviews were five star?

  * Vine: 0%
  * Non-Vine: 53.64%

![image](https://user-images.githubusercontent.com/96206626/165426740-b5b59cb8-50aa-4841-9e30-b0abcc52dfb2.png)


## Summary

After reviewing the results of this analysis, we have determined that there is NOT a positivity bias towards participants who participate in the Vine program, in fact the inverse is true as none of the 5 star reviews came from Vine participants. We would absolutely be able to add more depth to this analysis if we received additional information as to the distribution of star ratings from 1 - 5, not just the 5's.
