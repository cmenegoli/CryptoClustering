# CryptoClustering
## The code is used an unsupervised learning algorithm in Python to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.
-	Create a data frame with the scaled data and set the "coin_id" index.
### K-value algorithm
-	Find the Best Value for k Using the Original Scaled Data Frame
The best K value is 4 after the calculation.
-	Apply the K-means algorithm to cluster Cryptocurrencies.
### PCA & K-value algorithm
-	Perform a PCA to reduce the features to three principal components.
-	Calculate the total explained variance. The result is 0.8950316570309841.
-	Find the Best Value for k after PCA and the best K value is 4.
-	Apply the K-means algorithm to cluster Cryptocurrencies after PCA.
### Summary
-	The best clusters are 4 and the PCA reduced the dimensionality of the dataset and combine all variables/features tighter to generate new PCA variables. These provide us with better visualization for clustering. “market_plot” using K-Means from scaled dataset has some overlap. But after PCA, the dataset has been divided clearly into 4 clusters.