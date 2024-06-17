# Coustomer-ML
Customer Segmentation using K-Means Clustering
This project focuses on segmenting customers based on their annual income and spending score using K-Means clustering. The objective is to group customers into distinct clusters to better understand their behavior and tailor marketing strategies accordingly.

Dataset
The dataset (data.csv) contains information about customers including their annual income and spending score.

Workflow
Data Loading and Preprocessing:

Load customer data from CSV file into a Pandas DataFrame (df_customers).
Explore the dataset by displaying the first few rows, checking dimensions, and inspecting data types and missing values.
Exploratory Data Analysis (EDA):

Perform basic data exploration to understand the distribution of features and any potential relationships.
Clustering with K-Means:

Select specific columns (Annual Income and Spending Score) as features (X) for clustering.
Determine the optimal number of clusters using the Elbow Method to minimize Within-Cluster Sum of Squares (WCSS).
Apply K-Means clustering with the chosen number of clusters and visualize the clusters along with their centroids.
Results Visualization:

Plot the Elbow Method graph to identify the optimal number of clusters based on WCSS.
Visualize the clusters in a scatter plot using different colors for each cluster and mark centroids to represent the typical behavior of each segment.
Libraries Used
numpy for numerical operations.
pandas for data manipulation and analysis.
matplotlib and seaborn for data visualization.
sklearn for clustering (KMeans).
Conclusion
This project demonstrates the application of K-Means clustering to segment customers into meaningful groups based on their financial behavior. The identified clusters can assist businesses in targeted marketing strategies and personalized customer engagement, thereby enhancing customer satisfaction and business profitability.
