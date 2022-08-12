# Amazon_Vine_Analysis

## Overview of the analysis: 
The prupose of the analysis is to see if there is a bias between reviews under the vine porgram versus the review not under the vine program. This is done by filtering out certain information out of a databse that contains information about Amazon reviews. From there the datafram was cleaned up by narrowing down the reviews by how helpful the review was voted and then seperating into two dataframes; one for the reviews under the vine program and the other for those not under the vine program. 

## Results: 
<img width="1042" alt="Screen Shot 2022-08-12 at 1 12 33 PM" src="https://user-images.githubusercontent.com/102255823/184410638-48586d72-0536-42fa-ab36-200024f9f390.png">

- After seperating the reviews by the vine program, the rows of the two dataframes can be counted for distinct review ids and the total of reviews are 65,601 with 633 paid reviews and 64,968 unpaid reviews. 
- There are 222 five star vine reviews and 30,543 five star non-vine reviews. 
- Taking the number of five star reviews over the number total reviews gives the percentage of five star reviews for the vine program. The percent of five star vine reviews is 36.2 percent and the percent of five star non-vine reviews is 47.0 percent. 

## Summary: 
Based on the results of the analysis, there does not seem to be a positivity bias for the revirew under the vine program. If there was a bias, then there would be a high percentage of five star reviews in comparisons to the non-vine reviews. However, the results show that the percentage of five star reviews is less than the five star reviews that are not under the propgram. Therefore there is no bias. Another way to support thi claim is to find the percentage of 1,2,3,and 4 star reviews. Is there is a bias then there would be a higher precentage of 4 and 5 star reviews when compared to the non-vine reviews. 
