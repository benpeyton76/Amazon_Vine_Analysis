# ***Amazon Vine Analysis***

## ***Overview:***

In this project, SellBy has asked for an analysis of Amazon product reviews. The Amazon Vine program pays members to write and submit reviews of products provided by different manufacturers. The SellBy team will sort through these datasets that contains reviews of the provied products. By using PySpark, performing the ETL process to extract datasets, transform the data, and load the transformed data into Postgres will be the essential part of this project, which also requires connecting to an AWS RDS instance. Then, using PySpark to see if bias exists in favorable reviews from Vine members in the dataset. 

## ***Results:***

The Amazon reviews for musical instruments were used to perform this analysis.

* ***How many Vine reviews and non-Vine reviews were there?***
  
  <img width="480" alt="Deliverable 1a" src="https://user-images.githubusercontent.com/87077325/148458197-0072a490-8bec-4231-96cb-7ed05f4a1e3d.png">
 
  The total number of reviews are 14,533. Sixty reviews were from Vine members and 14,473 are non-Vine members.
  

  
* ***How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?***

  Out of the 60 Vine member reviews, 34 of them had been given 5 stars. Of the 14,443 non-Vine member reviews, 8210 reviewers gave a product review of 5 stars.
  


* ***What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?***

  The percentage of Vine reviews with 5 stars is 56.67%. The non-Vine members has a percetage of 56.73% of reviews that are ranked at 5 stars.
  
  

## ***Summary:***

As the above summary graphic shows, there is practically no bias between Vine and non-Vine members with a percentage of ~57% for both catagories. This shows that the majority of reviewers who sampled/purchased the products gave it 5 stars. There could be further exploration by reviewing the distribution across all star levels of all members. In order to get a better analysis of the surveyed products, all star level data should be scrutinized. This would provide a better understanding of the products being reviewed and how to improve them. It could also help manufacturers and retailers fine tune their inventory to better serve their clients.
