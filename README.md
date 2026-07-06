# Customer Segmentation using K-Means Clustering and PCA

## Project Overview

This project performs customer segmentation using the K-Means Clustering algorithm, an unsupervised machine learning technique. The dataset is preprocessed, standardized, reduced using Principal Component Analysis (PCA), and then clustered into different customer groups. The Elbow Method and Silhouette Score are used to determine the optimal number of clusters.


## Objectives

- Understand customer behavior using clustering.
- Reduce high-dimensional data using PCA.
- Find the optimal number of clusters.
- Visualize customer segments.
- Generate business insights based on customer groups.


## Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


## Project Structure

Customer_Segmentation_Project/
│
├── data/
│   └── customers.csv
│
├── output/
│   ├── clustered_data.csv
│   ├── elbow_plot.png
│   └── pca_plot.png
│
├── notebook.ipynb
├── requirements.txt
└── README.md


## Workflow

1. Import Libraries
2. Load Dataset
3. Explore Dataset
4. Handle Missing Values
5. Remove Unnecessary Columns
6. Encode Categorical Features
7. Standardize Data
8. Apply PCA
9. Find Optimal Clusters using Elbow Method
10. Evaluate using Silhouette Score
11. Apply K-Means Clustering
12. Visualize Clusters
13. Analyze Customer Segments
14. Save Clustered Dataset


## Machine Learning Algorithm

### K-Means Clustering

K-Means is an unsupervised learning algorithm used to divide customers into groups based on similar characteristics.

### Principal Component Analysis (PCA)

PCA reduces the number of features while preserving most of the information, making visualization easier.


## Evaluation Methods

- Elbow Method
- Silhouette Score


## Output

The project generates:

- Clustered customer dataset
- Elbow Method graph
- PCA Cluster Visualization
- Customer Segment Analysis


## Business Insights

The customers can be grouped into different categories such as:

- High Value Customers
- Budget Customers
- Regular Customers
- Premium Customers

These insights help businesses create targeted marketing strategies and improve customer satisfaction.

## Requirements

Install the required libraries using:

      pip install -r requirements.txt
