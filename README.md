# Amazon_Vine_Analysis
## Overview of the analysis

The goal of this analysis is to determine if there is any bias toward favorable reviews from Vine members. We'll also test if there is a link between the paid Amazon Vine program and the results. For our baseline, we only looked at products that had over 20 votes and took the top 50 percent. I am using Amazon’s cloud service AWS, Google Colab, and Pyspark to analyze Amazon’s reviews for Music.

## Results

Table below which shows a similar of the rating between the Vine and the non Vine campaign.

**How many Vine reviews and non-Vine reviews were there?**

![This is an image](https://github.com/Wrancher123/Amazon_Vine_Analysis/blob/main/images/Count%20of%20Reviews%20Vine.png)
![This is an image](https://github.com/Wrancher123/Amazon_Vine_Analysis/blob/main/images/Count%20of%20Reviews%20non%20Vine.png)

**How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?**

![This is an image](https://github.com/Wrancher123/Amazon_Vine_Analysis/blob/main/images/5-star%20Reviews%20%20Vine.png)
![This is an image](https://github.com/Wrancher123/Amazon_Vine_Analysis/blob/main/images/5-star%20Reviews%20non%20Vine.png)

## Summary

The purpose of this analysis is to find out if there is a bias in favor of positive reviews from Vine members. I looked at reviews that had more than 20 total votes and those that had equal or greater than 50%. I then selected those that were more likely to be helpful.

![This is an image](https://github.com/Wrancher123/Amazon_Vine_Analysis/blob/main/images/Total%20Vine%20Reviews.png)
![This is an image](https://github.com/Wrancher123/Amazon_Vine_Analysis/blob/main/images/Total%20non%20Vine%20Reviews.png)gi