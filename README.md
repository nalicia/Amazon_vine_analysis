# Amazon_vine_analysis
## Overview
This week I had the oppurtunity to work with Jennifer analyzing Amazon reviews. The amazon vine program is a service that alllows manufacturers and publishers to recieve reviews for products. I performed the ETL process to extract, transform, and connect the data to an RDS instance. Using Pyspark and Google Colab, I reviewed the data to find any bias in the reviews.

## Results
* There were a total of 4,291 Vine reviews. (Paid)

<img width="677" alt="Screen Shot 2022-04-05 at 10 08 20 AM" src="https://user-images.githubusercontent.com/94723290/161772767-a68c66d8-cec9-451c-9bdc-c14b015f1c27.png">

* There were a total of 1,781,706 Non-Vine reviews. (Unpaid)

<img width="669" alt="Screen Shot 2022-04-05 at 10 10 33 AM" src="https://user-images.githubusercontent.com/94723290/161773253-a111aa8f-8dc1-4a13-bd72-9e5e74ca9d27.png">

* Of the 4,291 Vine reviews 1607 had 5 stars.

<img width="662" alt="Screen Shot 2022-04-05 at 10 05 14 AM" src="https://user-images.githubusercontent.com/94723290/161772106-d9e1c43d-3b03-42a3-800d-5b769bcfe825.png">

* Of the 1,781,706 Non-Vine Reviews (Not paid) 1,025,317 had 5 stars.

* <img width="678" alt="Screen Shot 2022-04-05 at 10 05 42 AM" src="https://user-images.githubusercontent.com/94723290/161772196-9850584d-0c97-4243-9f37-4b5f24c8b286.png">

* 99% of the Non-Vine 5 star reviews were not paid for their reviews.
* 1% of Vine 5 star reviews were paid, for their reviews.

## Summary
I do not believe there was positivity bias in the Vine reviews. Considering the majority of the 5-star reviews were Non-Vine or unpaid, I believe they genuinely thought highly of the products. If I had to add one more analysis,I would focus on the verified purchases. Using the verified purchases would solidify that these reviews were genuine. 
