# CryptoClustering

# CryptoClustering

We learned about unsupervised machine learning this week and will be using this to predict if cryptocurrencies are affected by the 24 hour or 7 day price changes by using unsupervised machine learning. 

We were given a “crypto_market_data.csv” with crypto information, again we are focused on the 24 hour and 7 day price changes for cryptocurrencies in the csv file. These are the different methods we used to predict the 24 hour and 7 day price change:
1)	We found the best k value using the original scaled DataFrame.  Using the elbow method, we manually found what is the best k value
2)	We then cluster the cryptocurrencies with k-means using the original scaled DataFrame. We used the K-Means model to find the best value for k.
3)	We optimized the clusters with the Principal Component Analysis. We used the original scaled DataFrame to perform a PCA and reduced the features to 3 principal components. 
a.	Found the best k value using the PCA data – using the elbow method, which was determined as the same k valued in step 1 (which was 4)
b.	We used K-Means using the PCA data.

Our main question to answer was: What is the impact of using fewer features to cluster the data using K-Means? The clusters in the PCA scatter plot are more defined compared to the clusters using the elbow method.
