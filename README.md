# Amazon Vine Analysis

## **Overview of the analysis:** 
###### The purpose of this analysis was to analyze Amazon reviews, specifically from members of the paid Amazon Vine program.  Comparing the reviews from paid and non-paid members would be useful to determine whether there is a positivity-bias from paid reviews. The reviews included in this analysis were for luggage. Using the ETL process, an AWS RDS database was created with tables in pgAdmin. PySpark was used to transform the Dataframe to match the tables in pgAdmin. PySpark was then used to further analyze Vine reviews. 

## **Results**
###### The analysis was used to answer the following questions: 
- How many Vine reviews and non-Vine reviews were there? 

- **There were 21 Vine reviews and 6690 non-Vine reviews.

  ![Screen Shot 2022-05-20 at 5 08 19 PM](https://user-images.githubusercontent.com/98051208/169610716-5d44b0e3-6f6d-4a3e-8009-0d6571b12196.png)

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

- **There were 10 5 star Vine reviews and 3448 5 star non-Vine reviews. 
  
  ![Screen Shot 2022-05-20 at 5 10 55 PM](https://user-images.githubusercontent.com/98051208/169611007-e9b7d9be-2a37-454b-bf31-3a72de28eb76.png)
  
- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

- **Approximately 48% of Vine reviews were 5 stars, whereas 52% of non-Vine reviews were 5 stars. 
  
  ![Screen Shot 2022-05-20 at 5 12 15 PM](https://user-images.githubusercontent.com/98051208/169611174-5afcf8bf-ed47-4e14-970c-d96826690c79.png)

## **Summary**
###### Given the percentage of 5 star reviews are nearly equal for Vine and non-Vine members, there does not appear to be a positivity bias for paid reviews. An additional analysis of the average review rating across Vine and non-Vine members would be useful. Although the percentage of 5 star reviews may be roughly equal, there may be more 4, and even 3, star Vine reviews which could still indicate a positivity bias. Additionally, it would be useful to analyze reviews for other products aside from luggage.
