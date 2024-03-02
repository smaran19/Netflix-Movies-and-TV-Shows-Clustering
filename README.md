#Netflix-Movies-and-TV-Shows-Clustering
![Uploading Screenshot 2024-03-02 200321.png…]()

Netflix Recommender recommends Netflix movies and TV shows based on a user's favorite movie or TV show. It uses a a K-Means Clustering model to make these recommendations. These models use information about movies and TV shows such as their plot descriptions and genres to make suggestions..

💾 Project Files Description
This Project includes 2 executable files, 1 text files ,1 h5 file as well as 1 directories as follows:

Executable Files:
NETFLIX_MOVIES_AND_TV_SHOWS_CLUSTERING.ipynb - Includes all functions required for clustering operations and generates the model.h5 file after execution.
final_notebook_NETFLIX_MOVIES_AND_TV_SHOWS_CLUSTERING.ipynb - after execution, evaluation is done on the unseen data as in no_of_clusters.txt.
Output Files:
model.h5 - Model contains information about the clusters of the train set.
result.txt - Contains information about the elvatuation of the clusters using silluhoute score .
Source Directories:
Dataset - Includes all dataset for the training phase and testing phase of the model in the csv format.
-----------------------------------------------------

📖 Kmeans clustering
k-means clustering is a method of vector quantization, originally from signal processing, that aims to partition n observations into k clusters in which each observation belongs to the cluster with the nearest mean (cluster centers or cluster centroid), serving as a prototype of the cluster. This results in a partitioning of the data space into Voronoi cells. k-means clustering minimizes within-cluster variances (squared Euclidean distances), but not regular Euclidean distances, which would be the more difficult Weber problem: the mean optimizes squared errors, whereas only the geometric median minimizes Euclidean distances. For instance, better Euclidean solutions can be found using k-medians and k-medoids.
![177921083-3eef47d2-43d8-4c87-a027-5aebd7ba7304](https://github.com/smaran19/Netflix-Movies-and-TV-Shows-Clustering/assets/150596819/4d64a992-6b2e-4900-b710-400c69bc271c)

📖 Agglomerative Hierarchical clustering
The agglomerative hierarchical clustering algorithm is a popular example of HCA. To group the datasets into clusters, it follows the bottom-up approach. It means, this algorithm considers each dataset as a single cluster at the beginning, and then start combining the closest pair of clusters together. It does this until all the clusters are merged into a single cluster that contains all the datasets.

This hierarchy of clusters is represented in the form of the dendrogram![177921624-6f20d71d-cd54-4d56-a7b3-3e2399c14426](https://github.com/smaran19/Netflix-Movies-and-TV-Shows-Clustering/assets/150596819/93a39779-108f-419c-bc54-30faf6122c96)



