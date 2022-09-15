# Amazon_Vine_Analysis

## Overview 
For this project a dataset was selected from amazon reviews on US Digital Ebook Reviews and used Pyspark. The ETL process conducted to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. PySpark was used to perform an analysis to determine if there were any favorable review biases from the chosen vine dataset. A data set from amazon reviews regarding video games was selected. 

## Results
How many Vine reviews and non-Vine reviews were there in the dataset?
- There were a total of of 4,291 vine reviews in our dataset, and 40,471 non-vine reviews in the complete dataset.

![image](https://user-images.githubusercontent.com/106290364/190294125-6c6d73fb-c439-4a5a-8a46-d92ee3acf1c2.png)


How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- In the data set their was a total of 15,711 5-star reviews. 15,663 of the 5-star reviews were non-vine

What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- 38.2% of the five_star reviews were vine. 38.9% of the five_star reviews were non-vine

![image](https://user-images.githubusercontent.com/106290364/190294268-782a8069-a9dc-4a01-a606-620a5aea92dc.png)


## Summary 
-After further analyzing, there does not appear to be any positivity bias in this dataset since the percentages shown are very close at 38%. Therefor, the analysis of the vine program does not show any bias.
