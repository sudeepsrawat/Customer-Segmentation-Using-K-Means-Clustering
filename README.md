# Customer Segmentation Using K-Means Clustering

This repository contains a Jupyter Notebook that demonstrates the application of K-Means clustering for customer segmentation. The analysis utilizes the [Mall Customers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python), which includes demographic information and purchasing behavior of mall visitors.

## Dataset Overview

The dataset comprises the following features:

- **Customer ID**: Unique identifier for each customer.
- **Gender**: Gender of the customer.
- **Age**: Age of the customer.
- **Annual Income (k$)**: Annual income of the customer in thousand dollars.
- **Spending Score (1-100)**: A score assigned by the mall based on customer spending behavior and purchasing data.

## Analysis Steps

1. **Data Import and Exploration**: Load the dataset and perform exploratory data analysis to understand the distribution and relationships of the features.

2. **Data Preprocessing**: Handle missing values (if any) and select relevant features for clustering. In this analysis, 'Annual Income (k$)' and 'Spending Score (1-100)' are used.

3. **Elbow Method for Optimal Clusters**: Implement the Elbow Method to determine the optimal number of clusters by plotting the Within-Cluster Sum of Squares (WCSS) against different cluster counts.

4. **K-Means Clustering**: Apply the K-Means clustering algorithm with the optimal number of clusters identified.

5. **Visualization**: Visualize the resulting clusters along with their centroids to interpret the customer segments.

## Results

The analysis segments customers into distinct groups based on their annual income and spending scores. This segmentation can help businesses tailor marketing strategies and improve customer engagement by understanding the characteristics of each group.

## Dependencies

The following Python libraries are required to run the notebook:

- `numpy`
- `matplotlib`
- `pandas`
- `sklearn`

Ensure these packages are installed in your Python environment before executing the notebook.

## Usage

To explore the analysis:

1. Clone this repository to your local machine.
2. Ensure the required datasets are available in the same directory as the notebook.
3. Open the Jupyter Notebook and execute the cells sequentially to reproduce the analysis.

## References

- [Mall Customers Dataset on Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- [K-Means Clustering Algorithm - Analytics Vidhya](https://www.analyticsvidhya.com/blog/2019/08/comprehensive-guide-k-means-clustering/)

---
