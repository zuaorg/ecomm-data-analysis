# ecomm-data-analysis

* Processed and cleaned a Pakistani ecommerce dataset consisting of 1.05 Million data points, starting with handling missing data. Simplified the 'payment_method' feature to 2 distinct categories ('cash' and 'digital'), achieving dimensionality reduction. Identified and addressed price outliers below PKR 50 by replacing them with the average order price.
* Engineered a new categorical feature, 'price_category', by discretizing product prices into three distinct levels: 'Low' (PKR 0 to 399), 'Medium' (PKR 399 to 5500), and 'Large' (PKR 5500 and above) based on quartile analysis.
* Conducted exploratory data analysis, identifying the top 3 most frequently purchased product categories: 'Mobiles & Tablets', 'Men’s Fashion', and 'Women’s Fashion'. Utilized a Chi-Square Contingency test which indicated a strong association (high chi2_stat and very low p_value) between product categories and price categories.

* Raw data can be downloaded here: https://www.kaggle.com/datasets/zusmani/pakistans-largest-ecommerce-dataset?resource=download
