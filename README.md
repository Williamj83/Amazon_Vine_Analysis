# Amazon Vine Review analysis



## Overview of analysis


The purpose of this project is to determine whether paid Vine reviews influence the overall reviews of products. This was completed using Google Colab and pyspark. The data was based on reviews of lawn and garden products on Amazon.



### Resources


* Data Sources: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Lawn_and_Garden_v1_00.tsv.gz


* Software: Google Colab, pyspark, pgAdmin, AWS RDS and S3



## Tables 


Customers table


![customers_table](https://github.com/Williamj83/Amazon_Vine_Analysis/blob/main/Images/customers_table.png)




Products table


![products_table](https://github.com/Williamj83/Amazon_Vine_Analysis/blob/main/Images/products_table.png)



Review ID table


![review_id_table](https://github.com/Williamj83/Amazon_Vine_Analysis/blob/main/Images/review_id_table.png)



Vine table


![vine_table](Images/vine_table.png)



## Results


Vine and Non Vine Reviews

![Vine and Non Vine Reviews](https://github.com/Williamj83/Amazon_Vine_Analysis/blob/main/Images/vine_reviews.png)

Five Star Reviews

![Five Star Reviews](https://github.com/Williamj83/Amazon_Vine_Analysis/blob/main/Images/5%20star%20reviews.png)


## Summary


The products with Vine reviews did not have a higher percentage of 5 star reviews.  
The percentage of 5 star reviews for non-Vine reviewed products is higher.


