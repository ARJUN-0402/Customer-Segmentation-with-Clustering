# Customer Segmentation with Clustering

This project performs customer segmentation using K-Means clustering on the "Mall Customers" dataset.

## Project Overview

The goal of this project is to group customers into different segments based on their annual income and spending score. This information can be used by the marketing team to create targeted campaigns for each customer segment.

The project follows these steps:
1.  **Data Loading and Cleaning:** The "Mall Customers" dataset is loaded and cleaned.
2.  **Exploratory Data Analysis (EDA):** The data is explored to understand its characteristics and find relationships between features.
3.  **K-Means Clustering:** K-Means clustering is applied to segment the customers. The optimal number of clusters is determined using the Elbow Method and Silhouette Score.
4.  **Cluster Visualization:** The customer segments are visualized using a scatter plot.
5.  **Business Insights:** Actionable business insights are provided for each customer segment.

## Files Included

-   `customer_segmentation.py`: The main Python script that performs the customer segmentation.
-   `Mall_Customers.csv`: The dataset used for the project.
-   `genre_distribution.png`: A plot showing the distribution of genres.
-   `age_distribution.png`: A plot showing the distribution of ages.
-   `annual_income_k_distribution.png`: A plot showing the distribution of annual incomes.
-   `spending_score_1-100_distribution.png`: A plot showing the distribution of spending scores.
-   `pair_plot.png`: A pair plot showing the relationships between the numerical features.
-   `correlation_heatmap.png`: A heatmap showing the correlation between the features.
-   `elbow_method.png`: A plot showing the Elbow Method for finding the optimal number of clusters.
-   `customer_clusters.png`: A scatter plot showing the customer segments.

## How to Run the Project

1.  Make sure you have Python and the following libraries installed:
    -   `pandas`
    -   `numpy`
    -   `matplotlib`
    -   `seaborn`
    -   `scikit-learn`
2.  Run the following command in your terminal:
    ```bash
    python customer_segmentation.py
    ```
3.  The script will generate all the plots and print the cluster analysis results.
