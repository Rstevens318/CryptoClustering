# Crypto Clustering

In order to predict the affect of 24-hour or 7-day price changes on cryptocurrencies, we will use python and unsupervised machine learning. 

## Resources
- [Cryptocurrency Data](Resources/crypto_market_data.csv)

## Data With Original Scaled DataFrame

- DataFrame using StandardScalar

![Alt text](Images/OriginalScaledData.png)

- Elbow Method for Best `k` Value

![Alt text](Images/ElbowCurve.png)

- Scatter Plot 

![Alt text](Images/Clusters.png)


## Data with Principal Component Analysis (PCA)
- DataFrame using Principal Component Analysis (PCA)

![Alt text](<Images/PCA Scaled Data.png>)

- PCA Elbow Method for Best `k` Value

![Alt text](<Images/PCA ElbowCurve.png>)

- PCA Scatter Plot

![Alt text](<Images/PCA Clusters.png>)


## Tools and Technologies
 - Programming Language: Python
 - Libraries: Pandas, hvplot, scikit
 - Data Analysis: Exploratory data analysis, Pandas dataframes, Unsupervised Machine Learning