# Machine-Learning-Project-KNN-and-K-Means-Clustering
## Project Overview
This project demonstrates two key machine learning algorithms: K-Nearest Neighbors (KNN) and K-Means Clustering. The dataset used for KNN classification involves predicting a target class, while the K-Means clustering section focuses on grouping income data into distinct clusters.

## Key Concepts:
* K-Nearest Neighbors (KNN): A supervised learning algorithm used for classification tasks.
* K-Means Clustering: An unsupervised learning algorithm used to group data into distinct clusters.

## KNN Algorithm
* Dataset:
The dataset used for the KNN classification model (Classified Data.txt) consists of multiple features, with TARGET CLASS being the target variable.

* Steps Involved:
* 1.Data Preprocessing:
  * Data was split into training and testing sets.
  * Features were normalized using MinMaxScaler to bring all features into the same range.
* 2.Model Training:
  * KNN was applied for classification. We explored different values of k (from 1 to 40) to find the optimal number of neighbors by evaluating the error rate.
* 3.Model Evaluation:
  * The error rates for different values of k were plotted, and the optimal k was chosen.
  * Confusion matrix and classification report were generated to evaluate model performance.
* 4.Key Findings:
  * The best k-value was determined based on the error rate curve.
  * The model's accuracy, confusion matrix, and classification report provided insights into its performance on the test data.

## K-Means Clustering
* Dataset:
The dataset used for K-Means clustering (income.csv) includes age and income data of individuals.

* Steps Involved:
* 1.Before Normalization:
  A scatter plot of Age vs. Income was generated to visualize the data before applying clustering.
* 2.Clustering with K-Means:
  * K-Means clustering was applied with 3 clusters.
  * The centroids of each cluster were calculated and visualized using a scatter plot.
* 3.Data Normalization:
  The Age and Income columns were normalized using StandardScaler to ensure better performance of the clustering algorithm.
* 4.After Normalization:
  * A scatter plot of the normalized data was generated, followed by applying K-Means clustering again.
  * The centroids of the clusters were recalculated and visualized.
  
## Key Findings:
The clusters were well-separated after normalization, and the centroids provided insights into the characteristics of each cluster.
The final scatter plot with centroids effectively showed how the data was grouped.
