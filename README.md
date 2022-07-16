# Amazon_Vine_Analysis

# Overview
As Analyst for Big Market, the task was to help their new client $ellBy with marketing efforts for a new multi-product launch. $ellBy is also looking to start a program that will give free products to Vine subscribers in exchange for reviews of their products v. their competitors.
$ellBy is looking to be sure that ther is no positivity biased reviews within the group that received products for free. 

This is accomplished by comparing the positive reviews of those who are in the Vine program and those that are not.

The data was extracted from the Amazon website and read into a a Colab notebook by way of Spark. The Vine Analysis was accomplised using Pandas.

# Results

## Vine v. Non Vine Reviewers
**here we see that there are significantly more Non-Vine reviewers than Vine Reviewers**

![Total_Vine_Reviews.png](https://github.com/NShan9297/Amazon_Vine_Analysis/blob/main/ScreenShots/Total_Vine_Reviews.png)

**there are 261 total Vine Reviewers**

![non_vine_reviews.png](https://github.com/NShan9297/Amazon_Vine_Analysis/blob/main/ScreenShots/non_vine_reviews.png)

**there are 24,040 total Non-Vine Reviewers**

## 5 star Vine Reviews
![5_star_vine.png](https://github.com/NShan9297/Amazon_Vine_Analysis/blob/main/ScreenShots/5_star_vine.png)

## 5 star Non-Vine Reviews
![5_star_nonvine.png](https://github.com/NShan9297/Amazon_Vine_Analysis/blob/main/ScreenShots/5_star_nonvine.png)

## 5 star Vine Percentage 
![vine_user_percentage.png](https://github.com/NShan9297/Amazon_Vine_Analysis/blob/main/ScreenShots/vine_user_percentage.png)

**40.61 % of the Vine Reviews were 5 stars**

## 5 Star Non-Vine Percentage
![non_user_percentage.png](https://github.com/NShan9297/Amazon_Vine_Analysis/blob/main/ScreenShots/non_user_percentage.png)

**45.34% of the Non-Vine Reviews were 5 stars**
# Summary 
Overall, there does not appear to be a positivity bias. Comparatively, the figures are about the same. 
With a larger data set, there is a limit to where the numbers begin to add much value. With this very large data set, it appears that we may have reached this point.
There is less than 50% but more than 40% for both sets of reviwers. It appears that the customers each gave their honest opinion and were not swayed by having received 
the products they reviewed for free. 