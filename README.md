# CryptoClustering
Prediction if cryptocurrencies are affected by 24-hour or 7-day price changes using:
 - K-means algorithm for clustering
 - Elbow method/Calinski Harabasz score values for finding the optimal number of clusters
 - PCA to reduce dimentionality
 - StandardScaler for data normalization/rescaling
## Repository Contents
- *Crypto_Clustering.ipynb* with the scripts for clustering data <br>
- **Resources** directory contains:
    - *crypto_market_data.csv* file with input data <br>
- **Output** directory contains resulting Elbow Curves and Clustered Data plots <br>
## Installation
 - Having Python installed on your machine along with Jupyter Notebook available, clone this repository to your local machine <br>
## Usage
 - Run the *Crypto_Clustering.ipynb* script using Jupyter Notebook <br>

## Outputs
Elbow curves pattern is shared between the original data (7 features) and PCA 3-dimentional data. Visualization highlights that inertia values have significant drops till k=4, and then decrease slows down. So, k=4 is the most optimal choice for number of clusters for our data. <br>
<img src="https://github.com/ValentynaK17/CryptoClustering/blob/main/Outputs/Elbow.png" width="600"> <br>
Clusters for fewer dimensions look pretty well separated, unlike full set of features clustering result. <br>
<img src="https://github.com/ValentynaK17/CryptoClustering/blob/main/Outputs/Clusters.png" width="600">


