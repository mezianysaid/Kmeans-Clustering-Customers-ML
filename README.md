# Kmeans-Clustering-Customers-ML
 Kmeans  Clustering Algorithim for clustering the Custmers
A simple K-Means Clustering model implemented in python. The class KMeans is imported from sklearn.cluster library.
In order to find the optimal number of cluster for the dataset, the model was provided with different numbers of cluster ranging from 1 to 12. 
The 'k-means++' method to passed to the init argument to avoid the Random Initialization Trap.
The max_iter and the n_init were passed with their default values.

The WCSS ( or Within Cluster Sum of Squares ) was caluated and plotted to find the optimal number of clusters. 
The "Elbow Method" was used to find the optimal number of clusters.

Once the optimal number of clusters were found the model was reinitalised with the n_cluster arguments begin passed with the optimal number of clusters found using the "Elbow Method".

Finally, the clusters were visualised using scatter plot.
![kms](https://user-images.githubusercontent.com/79142324/174649579-51abb843-7d54-436c-803d-98513e2027a3.PNG)
