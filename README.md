# Amazon Vine Analysis
## Overview of Analysis
In this project we are analyzing the Amazon Vine program and determine if there is a bias in positive reviews from Vine members. For this project we are using PySpark to run an ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, load the transformed data into pgAdmin, and calculate various metrics.
## Results

Total number of reviews

- Vine Reviews 

![paid review](https://user-images.githubusercontent.com/66500222/184558290-0cdee7b2-5ce2-4abc-8e42-2a7fe98e1fa5.png)

- Non-Vine Reviews

![unpaid review](https://user-images.githubusercontent.com/66500222/184558303-679cbe57-d9ed-45a4-899d-c32e49faaac7.png)


Total number of 5-star reviews

- Vine Reviews 

![paid 5 star](https://user-images.githubusercontent.com/66500222/184558494-5847b626-f988-413d-9a26-0882887b1393.png)

- Non-Vine Reviews

![unpaid 5 star](https://user-images.githubusercontent.com/66500222/184558497-367f310a-9e47-44b4-8430-67b6f8e049af.png)

Percentage of 5-star reviews

- Vine Reviews 

![paid percentage](https://user-images.githubusercontent.com/66500222/184558639-c2b4e587-b8cd-4432-939e-99c6953e2471.png)


- Non-Vine Reviews

![unpaid percentage](https://user-images.githubusercontent.com/66500222/184558642-b4a5b309-070e-4471-9e3f-4a1444c8f9a2.png)

## Summary

We analyzed a large dataset of reviews, of which only 2287 were for the paid Vine program, compared to nearly 147512 non-Vine reviews. Of paid reviewers, 42% gave the product a five-star review, while 46% of unpaid reviewers gave a five-star. In conclusion, we determine that there is no bias in the reviews written by the Amazon Vine program.
Additionally, we analyzed the statistical distribution (mean, median, and mode) of star ratings for Vine and non-Vine reviews.


![statistical distribution](https://user-images.githubusercontent.com/66500222/184558898-9a0a2c6d-9257-4f9f-86bc-90e5a608a62f.png)
