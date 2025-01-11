# Customer-Segmentation-Using-K-Means-Clustering-in-R
This project demonstrates customer segmentation using the Mall Customers Dataset and the K-Means clustering algorithm in R. Customer segmentation is a key process for businesses to understand customer behavior and tailor their strategies accordingly.

Steps to do:

1. Set Up the Environment
Install and load the necessary R packages:
tidyverse for data manipulation and visualization
cluster for clustering algorithms
factoextra for visualizing clustering results

2. Load the Dataset
Use the Mall Customers dataset from an external URL.
Inspect the dataset structure and summary to understand the data.

3. Preprocess the Data
Select relevant columns: annual_income and spending_score.
Ensure data consistency and clean any missing or irrelevant information.

4. Determine Optimal Number of Clusters
Apply the Elbow Method to find the optimal number of clusters by plotting the within-cluster sum of squares (WSS) for different values of k.

5. Apply K-Means Clustering
Perform K-Means clustering with the chosen number of clusters (e.g., k = 5).
Assign cluster labels to the original dataset.

6. Visualize the Clusters
Use the factoextra library to create a scatter plot visualizing the clusters and their centroids.

7. Analyze and Interpret Results
Summarize the average annual income and spending score for each cluster.
Interpret the customer segments and suggest business strategies for each group.

Tools and Technologies:
Programming Language: R
Libraries: tidyverse, cluster, factoextra
Dataset: Mall Customers Dataset

OUTTPUT :

![r customer cluster](https://github.com/user-attachments/assets/135f0040-9cc6-4fe7-b009-179ee08c256d)

