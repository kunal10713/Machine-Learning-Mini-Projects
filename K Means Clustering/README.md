## K-means clustering

K-Means Clustering is an unsupervised learning algorithm that is used to solve the clustering problems in machine learning or data science.

K-Means Clustering is an Unsupervised Learning algorithm, which groups the unlabeled dataset into different clusters. Here K defines the number of pre-defined clusters that need to be created in the process, as if K=2, there will be two clusters, and for K=3, there will be three clusters, and so on.

It is an iterative algorithm that divides the unlabeled dataset into k different clusters in such a way that each dataset belongs only one group that has similar properties.

It allows us to cluster the data into different groups and a convenient way to discover the categories of groups in the unlabeled dataset on its own without the need for any training.

It is a centroid-based algorithm, where each cluster is associated with a centroid. The main aim of this algorithm is to minimize the sum of distances between the data point and their corresponding clusters.

The algorithm takes the unlabeled dataset as input, divides the dataset into k-number of clusters, and repeats the process until it does not find the best clusters. The value of k should be predetermined in this algorithm.

### The k-means clustering algorithm mainly performs two tasks:
  1. Determines the best value for K center points or centroids by an iterative process.
  2. Assigns each data point to its closest k-center. Those data points which are near to the particular k-center, create a cluster.
  
### Choosing the k value:

There is no easy answer for choosing a best case value.

However one way to try to do it is using something known as the elbow method:
  1. First of all you compute the sum of squared error otherwise known as SSE. For some values of k for example 2 4 6 8 etc.
  
 **SSE**: The sum of squared errors is defined as the sum of the square distance between each member of the cluster and its centroid.
  
  2. If you plot K against the SSE you will see that the error decreases as K gets larger. This is because in the number of clusters increases clusters should be smaller, so distortion is also smaller.
  
  3. The idea of the Elbow method is to choose the K at which the SSE decreases abruptly.
  
  
  







