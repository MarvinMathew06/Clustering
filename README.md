# Clustering -K Means method and Silhouette Score 
The different types of clustering includes:
1. K Means Clustering
2. Hierarchical Clustering
3. K Mode Clustering
4. DBScan Clustering — Density-Based Spatial Clustering

Among them, K-means is one of the most popular clustering algorithm. In this K clusters is created where data points in each of these K clusters are similar properties.

The idea is to create K clusters of data where data in each of the K clusters have greater similarity with other data in the same cluster

![image](https://user-images.githubusercontent.com/86583187/173986667-167a36d8-475d-4301-a665-02c2f6d1852b.png)


K-means algorithm belongs to the category, prototype-based clustering. Prototype-based clustering algorithms are based on one of the following: 

1. Centroid-based clusters: Each cluster built around a point which is termed as the centroid (average) of similar points with continuous features. K-means algorithm results in creation of centroid-based clusters.
2. Medoid-based clusters: Each cluster built around a point which is termed as the medoid which represents the point that minimises the distance to all other points that belong to a particular cluster, in the case of categorical features.
**
Working of K-means and optimization**

K means aims to reduce or minimise the sum of sqaured errors (SSE) within each clusters. SSE is the sum of the squared differences between each observation and the cluster centroid.At each stage of cluster analysis the total SSE is minimised with SSEtotal = SSE1 + SSE2 + SSE3 + SSE4 ….  + SSEn.
