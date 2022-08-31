# Amazon_Vine_Analysis

## Overview
  The purpose of this project is to analyize reviews written by members of the paid Amazon Vine Program.  In the Amazon Vine Program manufacturers and publishers pay a small fee to send products to members of the vine program who are then required to write a review of the product.  Using PySpark, I analyzed the dataset for US Toy reviews to determine if there is bias toward favorable reviews from Vine members.

## Results

![image](https://user-images.githubusercontent.com/104471775/187577188-4d80efb1-3608-4a24-a0f7-77ea2e4c11e1.png)  ![image](https://user-images.githubusercontent.com/104471775/187577383-399c9033-cb2b-4337-a4b0-a09130b0666e.png)

#### Number of Reviews
![image](https://user-images.githubusercontent.com/104471775/187578574-92f2cb81-7d5a-4bc3-8593-d6844d619e50.png)
* There were a total of 1,266 vine reviews and a total of 62,028 non-vine reviews.  Vine membership reviews accounted for only 2% of the total number of reviews gathered.

#### Number of 5-Star Reviews 
![image](https://user-images.githubusercontent.com/104471775/187579577-4fb8a4e2-0ff6-4ec0-9d3f-c318124d3800.png)
* Of the 1,266 reviews from Vine members, 432 reviewers gave a 5-star review.
* Of the 62,028 reviews from Non-Vine members, 29,982 reviewers gave a 5-star review.
* 34% of vine members provide a 5-star review, while 48% of non-Vine members provide a 5-star review.

![image](https://user-images.githubusercontent.com/104471775/187581408-abbed959-0f59-461f-896e-f07ec9f2c094.png)

## Summary
  There is no bias in favorable reviews from Vine membership.  Approximately 30% of Vine members provided 5-star reviews for the toy product that they received, while approximately 50% of non-Vine members provide a 5-star review.  Another analysis that could be performed to support this statement is to group toys by type and compare to the number of 5-star reviews to determine if a paid review creates bias among the different classification of toys.
