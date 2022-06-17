# Clustering -K Means method and Silhouette Score 
The different types of clustering includes:
1. K Means Clustering
2. Hierarchical Clustering
3. K Mode Clustering
4. DBScan Clustering — Density-Based Spatial Clustering

Among them, K-means is one of the most popular clustering algorithm. In this K clusters is created where data points in each of these K clusters are similar properties.

The idea is to create K clusters of data where data in each of the K clusters have greater similarity with other data in the same cluster

![image](https://user-images.githubusercontent.com/86583187/174216059-ca275575-7ca6-4bb6-b02d-51d6d00009b3.png)



K-means algorithm belongs to the category, prototype-based clustering. Prototype-based clustering algorithms are based on one of the following: 

1. Centroid-based clusters: Each cluster built around a point which is termed as the centroid (average) of similar points with continuous features. K-means algorithm results in creation of centroid-based clusters.
2. Medoid-based clusters: Each cluster built around a point which is termed as the medoid which represents the point that minimises the distance to all other points that belong to a particular cluster, in the case of categorical features.

Working of K-means and optimization

K means aims to reduce or minimise the sum of sqaured errors (SSE) within each clusters. SSE is the sum of the squared differences between each observation and the cluster centroid.At each stage of cluster analysis the total SSE is minimised with SSEtotal = SSE1 + SSE2 + SSE3 + SSE4 ….  + SSEn.

The objective function which needs to be minimized:

![image](https://user-images.githubusercontent.com/86583187/173990960-a14820cd-2e11-46c2-85aa-435212711c5e.png)

How to find most optimal value of K?
The technique used to find the most optimal value of K is draw a reduction in variation vs number of clusters (K) plot. Alternatively, one could draw the squared sum of error (SSE) vs number of clusters (K) plot. Here is the diagram representing the plot of SSE vs K (no. of clusters). In the diagram below, the point representing the optimal number of clusters can also be called as elbow point. The elbow point can be seen as the point after which the distortion/cluster inertia/SSE start decreasing in a linear fashion. 

Sum of Squared Error vs Number of Clusters plot using Elbow method
![image](https://user-images.githubusercontent.com/86583187/174216235-200b2b85-c70a-41fc-9ba0-caefb3e7f467.png)



