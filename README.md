# K-Means Clustering: An Introduction

## Introduction

Clustering is a type of unsupervised machine learning algorithm aimed at understanding relationships within datasets and grouping data points without predefined labels. One popular clustering algorithm is K-means. K-means, along with other clustering models, divides a dataset into groups so that data points within the same group are more similar to each other than to those in other groups.

## K-Means Algorithm

K-means is a statistical data analysis method used for clustering in data mining and pattern recognition. It involves grouping objects into clusters and finding similarities between them without prior knowledge of their classes.

### Algorithm Strategy

**Step 1: Define the Number of Clusters (K)**

Choose the number of clusters (K) that you want to classify your data into. This step sets the foundation for categorizing data points.

**Step 2: Randomly Choose Centroid Points**

Each cluster has a centroid, which is a central point. These centroids are initially selected and used to measure distances between data points using the Euclidean formula.

**Step 3: Assign Points to Clusters**

Assign data points to clusters by measuring the distance between each data point and each centroid in all clusters. A point belongs to the cluster whose centroid it is closest to.

**Step 4: Choose New Centroids**

Compute the mean of the data points in each cluster to find new centroids. Calculate the mean for both the x and y coordinates (or any relevant features).

**Step 5: Reassign Points to New Centroids**

Repeat the assignment process with the new centroids. Data points are reassigned to the cluster with the minimum Euclidean distance to its centroid.

**Step 6: Iterate**

Continue repeating steps 4 and 5 until there is no further change in cluster assignments.

**Defining the Best K Cluster**

Use the Within-Cluster Sum of Squares (WCSS) method to determine the optimal number of clusters. WCSS involves calculating the sum of squared distances between each data point and its cluster's centroid.

## Dataset

This example uses a dataset containing hypothetical customer data. It includes 200 records with the following features:

1. Customer ID
2. Customer Gender
3. Customer Age
4. Annual Income (in Thousand Dollars)
5. Spending Score (based on customer behavior and spending nature)

This dataset is intended for demonstrating how K-means clustering can categorize customers based on their features.
