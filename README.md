# Data-mining-in-IRIS-dataset
Two Clustering models were used in order to obtain best accuracy.

1.	K-Means Clustering:-

The Κ-means clustering algorithm uses iterative refinement to produce a final result. The algorithm inputs are the number of clusters Κ and the data set. The data set is a collection of features for each data point. The algorithms starts with initial estimates for the Κ centroids, which can either be randomly generated or randomly selected from the data set. 

•	Specify the desired number of clusters K: Let us choose k=2 for these 5 data points in 2-D space. 
•	Randomly assign each data point to a cluster: Let’s assign three points in cluster 1 shown using red color and two points in cluster 2 shown using grey color.
 
•	Compute cluster centroids: The centroids of data points in the red cluster is shown using red cross and those in grey cluster using grey cross.
 
•	Re-assign each point to the closest cluster centroids: Note that only the data point at the bottom is assigned to the red cluster even though it’s closer to the centroids of grey cluster. Thus, we assign that data point into grey cluster.
 

•	Re-compute cluster centroids: Now, re-computing the centroids for both the clusters.
 
•	Repeat steps 4 and 5 until no improvements are possible: Similarly, we’ll repeat the 4th and 5th steps until we’ll reach global optima. When there will be no further switching of data points between two clusters for two successive repeats. It will mark the termination of the algorithm if not explicitly mentioned.
