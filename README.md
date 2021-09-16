# Cryptocurrency Clusters



## Background

* Processing cryptocurrency data from an investment portfolio. Client is looking to create a classification system based on cryptocurrencies on the market.



## Approach

### Data Preparation

* Discarded all cryptocurrencies that are not being traded.
* Removed all rows that have have missing values.
* Filtered for cryptocurrencies that have been mined.
* Removed non-descriptive data 
* Converted categorical data to numeric data
* Standardized dataset so that larger values do not unduly influence the outcome.

### Dimensionality Reduction

* Used PCA to reduce the dimensionality of the data set, while preserving 90% of the explained variance. 

* Used t-SNE to further reduce data dimensions to 2 and visualize the output.

### Cluster Analysis with k-Means

* Created an elbow plot to identify the best number of clusters. 



## Recommendation

* I recommend using 4-5 cluster system for classifying cryptocurrency data.

