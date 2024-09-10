# Spotify Music Recommendation System

## Introduction

This project focuses on creating a music recommendation system based on customer preferences using clustering and content-based filtering techniques. The system utilizes various features from the music dataset to cluster similar tracks and recommend songs based on similarity metrics. The analysis involves data preprocessing, feature engineering, clustering, dimensionality reduction, and generating music recommendations.

## Project Structure

The project is structured as follows:

### Data Loading and Preprocessing

1. **Loading the Data**: Import the dataset from a CSV file.
2. **Initial Inspection**: Check the first few rows and get an overview of the dataset.
3. **Data Cleaning**:
   - Convert 'duration_ms' to minutes and rename it to 'duration_m'.
   - Drop duplicate rows and unnecessary columns.
   - Handle missing values and outliers by replacing them with mean values based on 'track_genre'.

### Exploratory Data Analysis (EDA)

1. **Data Exploration**: Analyze distributions of numerical columns and plot histograms.
2. **Correlation Analysis**: Compute and visualize the correlation matrix.
3. **Scatter and Box Plots**: Visualize relationships and distributions of numerical features.

### Feature Engineering and Encoding

1. **Categorical Encoding**: Convert categorical variables to numerical format using label encoding and one-hot encoding.
2. **Scaling**: Normalize numerical variables using MinMaxScaler.

### Clustering

1. **Optimal K Selection**: Use the Elbow Method to determine the optimal number of clusters for KMeans.
2. **Apply KMeans Clustering**: Cluster data into groups and add cluster labels to the original dataset.

### Dimensionality Reduction

1. **PCA**: Reduce dimensionality to 2D for visualization.
2. **t-SNE**: Further visualize high-dimensional data in a 2D space.

### Visualization

1. **Cluster Visualization**: Use scatter plots to visualize the clusters.
2. **Word Clouds**: Generate word clouds to represent frequently occurring genres in each cluster.

### Recommendation System

1. **Preprocessing for Recommendations**: Prepare data for content-based filtering by combining text features with numerical features.
2. **Cosine Similarity**: Compute similarity scores between tracks.
3. **Recommendation Function**: Implement a function to recommend songs based on similarity.

### Key Features

- **Data Preprocessing**: Handling missing values, duplicates, and outliers.
- **Feature Engineering**: Creation of new features and encoding categorical variables.
- **Clustering**: Application of KMeans clustering and visualization of clusters.
- **Dimensionality Reduction**: Use of PCA and t-SNE for data visualization.
- **Recommendation System**: Content-based filtering using cosine similarity for song recommendations.
- **Visualization**: Histograms, scatter plots, and word clouds to explore and present data.

### Contributing

Contributions are welcome! Please fork the repository, create a new branch, and submit a pull request for review.



