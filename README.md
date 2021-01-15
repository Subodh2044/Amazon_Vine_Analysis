# Amazon_Vine_Analysis

## Overview of the Analysis

The goal of this analysis is to analyze the reviews posted by the members of the paid Amazon Vine programs which allows manufacturers and publishers to receive the reviews. SellBy pays a fee to Amazon in exchange of providing products to Vine members, when are then required to publish a review. For the dataset that contains reviews for musical instruments, I leveraged PySpark for ETL process to extract, transform and Load to the pgAdmin, then analyzed data to determine any bias towards favorable reviews from the Vine members in the dataset.

## Results

1. There reviews for Vine members and non-Vine members are 60 and 1447 respectively.

![image](https://user-images.githubusercontent.com/67131400/104547271-beb6d880-55f3-11eb-8a28-ee61714051d2.png)
![image](https://user-images.githubusercontent.com/67131400/104547308-d5f5c600-55f3-11eb-9aaa-dbbbbfec7a4c.png)

2. For Vine member reviews 34 out of 60 are 5 stars wheresas for non-Vine members 8212 were 5 stars.

![image](https://user-images.githubusercontent.com/67131400/104547262-b9598e00-55f3-11eb-8405-3ee2cbdeba59.png)
![image](https://user-images.githubusercontent.com/67131400/104547297-cfffe500-55f3-11eb-9ec5-4918f65a3b7e.png)

3. 56.67% and 56.72% of the 5 star ratings were for Vine members and non-Vine-members respectively

![image](https://user-images.githubusercontent.com/67131400/104547273-c4142300-55f3-11eb-8ef9-d168394e9d5d.png)
![image](https://user-images.githubusercontent.com/67131400/104547322-dee69780-55f3-11eb-91c4-b8ee3de92028.png)


Analysis is using paid and uppaid variable which might result in bias. Hence, perchase verification should be analyzed to find the veracity of the reviews for the products and ensure the reviewers actually bought the products.
