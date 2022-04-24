# Analysis of Customer Personality and Spending

## About
This is a Mini-Project for SC1015 (Introduction to Data Science and Artificial Intelligence) which focuses on comparing the benefits and drawbacks of 2 types of data modelling on the same dataset. 

![image](https://user-images.githubusercontent.com/29501392/164968845-95d326ea-720e-419f-a1c0-1fecbf2d2d08.png)

## Contributors

- @jordanlianhs - Exploratory Data Analysis, Cross-Validation & Random Forest
- @nur-hazim - Clustering & Presentation
- @sufyanjais - Data Cleaning & Clustering
---
## Problem Definition

- Finding significant variables that determine if a customer accepts a company's current promotions
- Identify differences in the 2 models used
---
## Models Used

1. Random Forest Classification
2. K-Means++ Clustering
---
## Conclusion

`Similarities in both Models` 
- Classification & Clustering allows us to find the key variables that determine promotion campaign acceptance

`Differences in conclusions from Classification and Clustering`

**Classification**
- Classification points towards Frequency of Visits as a good indicator of campaign acceptance
- Customers with high spending on Wine, Gold and Meat can be persuaded to accept campaigns
- Lower income customers are least likely to accept campaigns
- Should provide for loyal customers by anticipating their behaviour
- Should provide membership benefits for for Wine, Gold and Meat buyers
- Should also add discounts for essential goods for lower income customers

**Clustering**

- Clustering grouped customers based on income
- Cluster 2 had high income, high education and high rate of campaign acceptance
- Cluster 3 had lowest income, lowest total spending, and accepted the least campaigns (undergrads and grads)
- Clusters 0,1 had highest spending on wine, but offer acceptance is neither bad or good
- Should provide Cluster 2 with more member benefits to persuade more campaign acceptance
- Should provide Cluster 3 with more student deals and promos
- Should provide Clusters 0,1 with more wine promos and wine campaigns

## What did we learn from this project?

- Classification and Clustering are useful ML approaches for businesses
- Both can be used in different ways to better understand customers
- Using ML to analyse, profie and target customers, companies can establish devoted customer base and return on investment in ML

## References

- <https://scikit-learn/stable/modules/cross_validation.html>
- <https://www.dotactiv.com/blog/classification-vs-clustering>
- <https://www.kaggle.com/imakash3011/customer-personality-analysis>
- <https://thecleverprogrammer.com/2021/02/08/customer-personality-analysis-with-python/>
- <https://medium.com/analytics-vidhya/effect-of-outliers-on-k-means-algorithm-using-python-7ba85821ea23>
- <https://doi.org/10.1142/9789813235533_0018>
- <https://theory.stanford.edu/~sergei/papers/vldb17-km.pdf >

