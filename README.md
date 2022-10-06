# Amazon_Vine_Analysis

## Overview of the analysis
- In this project, we had access to approximately 50 datasets. Each one contained reviews of a specific product, from clothing apparel to wireless products. We needed to pick one of these datasets and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, we used PySpark, Pandas, or SQL to determine if there was any bias toward favorable reviews from Vine members in our dataset. Then, we wrote a summary of the analysis for Jennifer to submit to the SellBy stakeholders.
I picked reviews for Home Entertainment products.

## Results: 
- How many Vine reviews and non-Vine reviews were there?
  - <img width="406" alt="paid_total" src="https://user-images.githubusercontent.com/89552059/194427973-30e6e57b-1cd0-42e2-b4d1-c08cb23a8f85.png">
  - <img width="447" alt="unpaid_total" src="https://user-images.githubusercontent.com/89552059/194427976-724aa3b8-51ef-499d-8899-1c7a46b47401.png">
  - We can see that the total number of paid reviews is 261, and the total number of unpaid reviews is 24,032.

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  - <img width="685" alt="paid_5star" src="https://user-images.githubusercontent.com/89552059/194428354-fbd22cc4-2279-4f51-8741-4cc725992768.png">
  - <img width="722" alt="unpaid_5star" src="https://user-images.githubusercontent.com/89552059/194428362-5aa791f4-76d5-46ef-83f0-7d2f0ae9ed6a.png">
  - Paid five-start reviews comprised 106 reviews, and unpaid five-start reviews totaled 10,894. 

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  - <img width="643" alt="paid_percentage" src="https://user-images.githubusercontent.com/89552059/194428760-42d5eaf9-8e97-4e3d-8c29-c405478a8756.png">
  - <img width="683" alt="unpaid_percentage" src="https://user-images.githubusercontent.com/89552059/194428771-19c75481-9c6e-4f08-b0e7-f50cfdac1191.png">
  - The percentage of Vine reviews resulted in about 41 percent, while non_Vine reviews resulted in about 45 percent.
  
  ## Summary:
  - According to our analysis, we can conclude that there is no strong positivity bias for reviews in the Vine program. Vine reviews had only 261 reviews compared to 24,032 non_vine reviews, and five-start reviews had only 106 compared to 10,894 non_Vine reviews, proving that Vine reviews had minimal effect on customers' decisions. 
  - To support our conclusion, we could calculate the total number of reviews and determine paid reviews ratio to non-paid reviews, which should be a minimum number in our case.
