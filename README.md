# Fifa-players-K-cluster-scratch-
K means clustering algorithm built from scratch on the 2020 Fifa players 


## Overview

This project involves clustering FIFA 20 player data using the k-means clustering algorithm and exploring patterns within player attributes such as overall rating, potential, wage, value, and age. The goal is to group players with similar characteristics into clusters for better understanding and analysis.

## Data Processing

Selected Features
The analysis focuses on the following player attributes:

Overall Rating
Potential
Wage (in Euros)
Value (in Euros)
Age
Data Cleaning and Scaling
Rows with missing values in the selected features were removed.
Min-Max scaling was applied to normalize values to a scale of 1-10.
K-Means Clustering

- Random Initialization of Centroids
Random centroids were generated as an initial step for the k-means clustering algorithm.

- Euclidean Distance and Label Assignment
Labels were assigned to data points based on the Euclidean distance to the centroids.

- Iterative Updates
Centroids were recalculated based on the geometric mean of each cluster, and the process iterated until convergence or a maximum number of iterations (100) was reached.

- Visualization
The clustering process was visualized in 2D space using Principal Component Analysis (PCA), showing the progression of clusters across iterations.



## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
