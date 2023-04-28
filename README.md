This repository includes code for DS5720 Social Network Analysis final project.

# Project

Amazon KDD Cup ‘23, Task 1 Next Product Recommendation (https://www.aicrowd.com/challenges/amazon-kdd-cup-23-multilingual-recommendation-challenge/problems/task-1-next-product-recommendation)

# Data

The Multilingual Shopping Session Dataset is a collection of anonymized customer sessions containing products from different locales, which consists of user sessions and product attributes. User sessions are a list of products that a user has engaged with in chronological order, while product attributes include various details like product title, price in local currency, brand, color, and description. Only the locales of English, German, and Japanese will be used in task 1. The proportion of each language is about 10:1:1.

# Goal

This project aims to predict the following product that a customer is likely to engage with, given their session data and the attributes of each product. The evaluation metric for Task 1 is the Mean Reciprocal Rank (MRR).

# Methods

- Most Popular Products, selecting top k popular items in the session of all users

- GNN (link prediction), leveraging both content information (features) and graph structure (interactions)

- RNN (next feature prediction, candidates selection, candidates ranking), processing sequential data with information from previous inputs

# Reference

- “Two-Stage System Using Item Features for next-Item Recommendation | Elsevier Enhanced Reader.” Accessed April 27, 2023. https://doi.org/10.1016/j.iswa.2022.200070.

# Contributors

- Yiwen Chen (yiwen.chen@vanderbilt.edu)

- Jingyuan Wu (jingyuan.wu@vanderbilt.edu)

- Tinglei Wu (tinglei.wu@vanderbilt.edu)
