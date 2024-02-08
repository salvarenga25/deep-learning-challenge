# deep-learning-challenge
 Due Jan 25th, 2024

# Analysis

## Overview
This analysis has been made with the intention to predict which applicants from the Alphabet Foundation has the best chances of successfuly fund their ventures.

## Results
- Target Variables: **IS_SUCCESSFUL** column from application_df

- Feature Variables: All the columns from `application_df` once **IS_SUCCESSFUL** column is dropped from the dataframe

- Variables to be removed: `EIN` and `NAME` columns


- I have 4 layers, 30 on the first one, 40 in the second one, 50 in the third one and 5 in the fourth one, based on testing I found that accuracy gets better with more layers and more neurons

- I wasn't able to achieve 75% of accuracy however i was close with a 73.13%

- In order to increase model performance I increased the number of neurons on the first layers and then decrease it on the last ones

## Summary

-  Removing more columns from the dataset could help to improve model performance, adding more layers and increasing the number of epochs (at least 50).


