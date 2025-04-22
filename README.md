# SeabornProject419
Seaborn Project for CPSC419 (Data Mining) using the diamonds dataset.

<br>

## Supervised

The Supervised learning process attempts to correlate the price (generalized into three categories) with the carat, depth, and table. This process used:
1. Linear Regression

       Linear Distribution classifies by a linear estimate of a response variable (dependent variables)
       by using the given regressors (independent variables).

3. Random Forest Classification

       Random Forest Classification uses several decision trees in order to predict the value of a given point, which is then
       bagged and the majority vote becomes the estimated group for the point. This is repeated for every point in the dataset.

<br>

## Unsupervised
The Unsupervised learning process attempts to compare the clustering efficiency of four different clustering algorithms, being:

1. Density-Based Clustering of Applications with Noise (DBSCAN)

       DBSCAN attempts to categorize the data points into three different groups:
        1. Core points
        2. Boundary Points
        3. Outlier Points

3. Ordering Points To Identify Clustering Structure (OPTICS)

       Similar to DBSCAN, OPTICS focuses on interpreting core distances and reachability distances.
   
       OPTICS builds a reachability graph instead of clusters, though the graph can be represented as clusters.

5. k-Means

       K-Means works by randomly assigning centroids, building clusters around them, and then updating the centroids based on
       point proximity. This continues until the centroids stop being reassigned.
   
       K-Means requires a predefined number of centroids.

7. Gaussian Mixture Model (GMM)

       Gaussian Mixture Model uses soft clustering, comprised of several Gaussians.
   
       This gives each point multiple cluster assignments with a grouping probability tied to them.
