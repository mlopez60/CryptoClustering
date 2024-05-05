# CryptoClustering

This challenge involved using Python and unsupervised learning to predict if cryptocurrenciesare affected by 1 day vs 7 day price changes. 

The following process was used to tackle this challenge: 
* Analyze data in a DataFrame
* Normalize data for further analysis
* Find the best K value using the normalized data - 4 was the best for this scenario
* Cluster the data using the Kmeans value
* Optimize the data using PCA
* Using the PCA data, find a best K value - In this situation, 3 and 4 were very similar but for the sake of the comparison, I went with 3. 
* Using the new K value, cluster the data. 
* Compare both clusters and see the impact of minimizing K value.


This was an interesting challenge but it gave me my biggest issue when comparing the two different best K values, as 3 and 4 looked very similar to me both times. I am unsure if there is another step to take to further differentiate the two. 