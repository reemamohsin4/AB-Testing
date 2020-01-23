# AB-Testing

Using the data provided in ab_data.csv, I run multiple tests to evaluate whether an e-commerce company should 
launch a new landing page on their website in order to increase conversion rates of users.

I perform three different tests:

* a hypothesis test using simulated samples of the given data
* a z-test
* a logistic regression model

## Source data

* `ab_data.csv`
* `countries.csv`

## Preparing data

After reading the data from `ab_data.csv` into a Dataframe, I explore the table and address untidy, missing, and duplicated data. 

## Manual Probability

Once my data is cleaned and prepared for analysis, I use `.mean()` to manually calculate the proportion of users in both the control and treatment group that converted.
