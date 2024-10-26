# Mall-Custmoers-Project
The goal of this project is to segment customers based on their annual income and spending score to identify distinct groups that can help inform targeted marketing strategies and enhance customer engagement.

Dataset:
The dataset used in this project contains customer information, specifically focusing on two key features:

Annual Income (in thousands): This feature represents the customer's income level.
Spending Score (1-100): This score reflects the customer's purchasing behavior and loyalty.
Methodology:

Data Preparation: The dataset was cleaned and preprocessed to ensure that there were no missing or irrelevant values.

K-means Clustering:

Implemented K-means clustering to group customers into five clusters based on the selected features.
The optimal number of clusters (K) was determined using the Elbow Method, which evaluated the Within-Cluster Sum of Squares (WCSS) for different values of K.
Model Training:

The K-means model was trained on the dataset, generating cluster centroids that represent the average characteristics of each customer segment.
Cluster Assignment: Each customer was assigned to the nearest cluster based on their income and spending score.

Evaluation:
The quality of the clustering was assessed using metrics such as Silhouette Score and Davies-Bouldin Index, which indicated the coherence of clusters.
Visualizations were created to represent the clusters and centroids, providing a clear overview of customer segmentation.
Results:

The project successfully identified five distinct customer segments based on their income and spending behaviors.
Visualization of the clusters revealed patterns that can be leveraged for targeted marketing strategies.
#Conclusion: This project demonstrates the effectiveness of K-means clustering in customer segmentation, providing valuable insights for businesses to tailor their marketing efforts and optimize resource allocation. Future work may involve incorporating additional features and exploring different clustering algorithms for improved results.
