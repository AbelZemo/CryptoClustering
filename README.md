# CryptoClustering
## Steps to Follow:
### Prepare the Data:
Description:
Prepare the data by creating a DataFrame with scaled values. Set the "coin_id" index from the original DataFrame as the index for the new DataFrame.
### Find the Best Value for k Using the Original Scaled DataFrame:
Description:
Utilize the elbow method to determine the optimal value for k based on the original scaled data.
### Cluster Cryptocurrencies with K-means Using the Original Scaled Data:
Description:
Cluster the cryptocurrencies using the original scaled data with K-means algorithm, considering the optimal value of k obtained in the previous step.
### Optimize Clusters with Principal Component Analysis:
Description:
Perform Principal Component Analysis (PCA) on the original scaled DataFrame to reduce the features to three principal components, thus optimizing the clusters.
### Find the Best Value for k Using the PCA Data:
Description:
Determine the best value for k using the elbow method applied to the PCA-transformed data.
### Cluster Cryptocurrencies with K-means Using the PCA Data:
Description:
Cluster the cryptocurrencies using the PCA-transformed data, considering the optimal value of k obtained from the PCA analysis.

Screenshots:
![1](screenshots/1.png)
![2](screenshots/2.png)
![3](screenshots/3.png)
![4](screenshots/4.png)
![5](screenshots/5.png)
![6](screenshots/6.png)



## What is the impact of using fewer features to cluster the data using K-Means?

Using fewer features to cluster data with K-Means can have several impacts:

#### Loss of Information: 

By using fewer features, you may lose important information that could potentially help in better clustering. This could lead to less accurate clustering results.

#### Dimensionality Reduction: 

Using fewer features effectively reduces the dimensionality of the data. While this can simplify the computational complexity of clustering algorithms like K-Means, it can also lead to oversimplification, potentially ignoring important patterns or relationships in the data.

#### Increased Sensitivity to Noise: 

With fewer features, the algorithm becomes more sensitive to noise or irrelevant features, which can lead to less robust clustering results.

#### Biased or Distorted Clustering: 

If the features omitted are important for distinguishing between different clusters, the clustering algorithm may produce biased or distorted clusters that do not accurately represent the underlying structure of the data.

####  Faster Computation: 

Fewer features mean fewer calculations, leading to faster computation times. This can be advantageous when dealing with large datasets or when computational resources are limited.

####  Improved Interpretability: 

On the positive side, using fewer features might lead to more interpretable clusters, as the relationships between fewer variables are easier to understand and visualize.

#### Potential Overfitting Reduction: 

If the original dataset contains redundant or irrelevant features, using fewer features may help in reducing overfitting and improving the generalization ability of the clustering model.

In summary, while using fewer features can simplify computation and potentially improve interpretability, it can also lead to loss of important information and less accurate clustering results if the omitted features are relevant for distinguishing between different clusters.

