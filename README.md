# Amazon_Vine_Analysis

## Purpose
The purpose of the analysis is to determine if there are any is bias toward reviews in the Vine program, which is a service that allows companies to receive reviews on their products from Amazon.  The companies pay Amazon to give products to the reviewers to publish reviews.  

The analysis has been completed on the Pet Products dataset from Amazon Review Datasets found [here](https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt).

The anlaysis used PySpark to perform the ETL and the analysis of Vine Reviews.

## Results 

### Total Number of Reviews
- Total Paid Reviews

![alt_text](https://raw.githubusercontent.com/bweirich/Amazon_Vine_Analysis/main/images/Total_Paid.PNG)
- Total Unpaid Reviews

![alt_text](https://raw.githubusercontent.com/bweirich/Amazon_Vine_Analysis/main/images/Total_Unpaid.PNG)

### Total 5 Star Reviews
- Total Paid 5 Star Reviews

![alt_text](https://raw.githubusercontent.com/bweirich/Amazon_Vine_Analysis/main/images/Total_Paid_5.PNG)
- Total Unpaid 5 Star Reviews

![alt_text](https://raw.githubusercontent.com/bweirich/Amazon_Vine_Analysis/main/images/Total_Unpaid_5.PNG)

### Percentage of 5 Star Reviews
- Percentage of Paid 5 Star Reviews

![alt_text](https://raw.githubusercontent.com/bweirich/Amazon_Vine_Analysis/main/images/Percent_Paid_5.PNG)
- Percentage of Unpaid 5 Star Reviews

![alt_text](https://raw.githubusercontent.com/bweirich/Amazon_Vine_Analysis/main/images/Percent_Unpaid_5.PNG)

## Summary
The percentage of unpaid reviews (62.32%) is higher then that of the paid reviews (42.52%) indicating that there is not positive bias for reviews in the Vine program.  There is a much higher number of unpaid reviews (99.61%) compared to paid reviews (0.39%) which should be taken into consideration.  Additionally you could view the distribution of star ratings for paid and unpaid reviews to compare the overall star ratings of one group to the other.
