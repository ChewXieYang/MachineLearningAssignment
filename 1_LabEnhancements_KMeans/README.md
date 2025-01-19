# K-Means Clustering Analysis
This Jupyter Notebook performs K-means clustering on driver behavior data.

## Key Features
* Data Preprocessing: Cleans the dataset, handles missing values, and ensures numeric data for clustering.
* EDA: Summarizes dataset structure and visualizes key patterns.
* Clustering: Implements K-means clustering with visualized results.

## Dataset
The dataset (driver-data.csv) includes:
* id: Driver ID
* mean_dist_day: Average daily distance
* mean_over_speed_perc: Percentage of time speeding

## Usage
* Install dependencies:
```
pip install numpy pandas matplotlib seaborn scikit-learn
```

* Run the notebook to process the data and generate clusters.

## Output
* Visualized clusters
* Silhouette scores for quality evaluation
