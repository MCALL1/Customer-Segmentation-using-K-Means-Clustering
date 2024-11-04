Customer Segmentation using K-Means Clustering

This project demonstrates the application of K-Means clustering for customer segmentation, utilizing a dataset of mall customers with attributes like annual income and spending score. Through this analysis, distinct customer groups are identified, helping to better understand patterns in customer behavior and spending.
Project Overview

The goal of this project is to segment customers based on their annual income and spending score. By using K-Means clustering, we can categorize customers into different segments, which is valuable for targeted marketing strategies. The project includes three main stages:

    Exploratory Data Analysis (EDA)
    Optimal Cluster Selection and Model Training
    Cluster Visualization

1. Exploratory Data Analysis (EDA)

To better understand the data, several EDA techniques are used:

    Scatter Plot: Visualizes the distribution of Annual Income (k$) vs. Spending Score (1-100) to observe potential clusters.
    Pair Plot: Displays relationships between multiple features (including Age, Annual Income, and Spending Score) to identify correlations and patterns in customer behavior.
    Basic Statistics: Calculates mean, median, and other statistics to observe general trends in customer behavior.

2. Optimal Cluster Selection and Model Training

The optimal number of clusters is determined using the Elbow Method:

    Elbow Method: Plots the inertia (sum of squared distances from each point to its assigned cluster center) for various values of kk (number of clusters). The "elbow" point in the graph suggests the optimal number of clusters, balancing model simplicity with accuracy. For this dataset, 5 clusters were chosen as the optimal number.

Using this optimal value, the K-Means clustering algorithm is applied to segment customers based on standardized features.
3. Cluster Visualization

The final step involves visualizing the customer segments created by the model:

    Cluster Plot: Plots customer data points, colored by cluster, to visually inspect the segmentation. This plot illustrates how different customer groups are distributed across income and spending score levels, providing a visual understanding of distinct customer types.

Key Processes and Models

    Clustering Algorithm: K-Means Clustering
    Feature Scaling: Standardization with StandardScaler to improve clustering effectiveness.
    Visualization Techniques: Scatter plot, pair plot, and cluster plot with Seaborn and Matplotlib for visual insights.

This project showcases a complete workflow for customer segmentation, from EDA to model selection and visualization. The resulting clusters provide valuable insights into customer behavior patterns, offering a foundation for targeted marketing and tailored business strategies.

  Real-World Applications

    Targeted Marketing: Businesses can focus their marketing efforts on specific customer segments identified by the clustering model (e.g., sending luxury product ads to high-income, high-spending segments).
    Product Recommendation: Recommender systems can be tailored to different customer segments, improving user experience.
    Customer Retention: Identifying at-risk customer segments (e.g., low spending, low interaction) for targeted retention strategies.
