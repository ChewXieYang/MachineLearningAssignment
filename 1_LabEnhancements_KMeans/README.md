K-Means Clustering Analysis

This Jupyter Notebook implements K-means clustering to analyze driver behavior based on provided data. It includes steps for data preprocessing, clustering, and visualization.

Features
Data Preprocessing:

Loading the dataset (driver-data.csv) and handling missing or inconsistent values.
Stripping whitespace from column names and ensuring the dataset contains numeric data for clustering.
Filling missing values with column means.

Exploratory Data Analysis (EDA):

Overview of dataset structure, including data types, missing values, and summary statistics.
Visualization of key patterns to understand data distribution.

Clustering Techniques:

Implementation of K-means clustering with optimized parameters.
Visualization of clustering results.

Libraries Used:

numpy
pandas
matplotlib
seaborn
sklearn

Dataset
The dataset used in this analysis (driver-data.csv) includes three columns:

id: Unique identifier for each driver.
mean_dist_day: Average distance driven per day.
mean_over_speed_perc: Percentage of time spent driving above the speed limit.

How to Use
Install dependencies:
Ensure you have Python installed along with the necessary libraries. You can install the required libraries using the following command:

pip install numpy pandas matplotlib seaborn scikit-learn

Run the notebook:
Execute the Jupyter Notebook to perform the clustering analysis.

Modify Parameters:
Adjust the K-means parameters (e.g., n_clusters) to explore different clustering results.

Results
The notebook provides:

Visualization of clusters.
Silhouette scores to evaluate clustering quality.