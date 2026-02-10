# Principal-Component-Analysis
PCA is a dimensionality reduction technique. It is used to transform high-dimensional data to 2 dimensions; while mainting essentional information. This techniques is commonly used in image and signal processing, facial recognition, and customer segmentation in marketing.
# Overview
This notebook demonstrates dimensionality reduction using PCA to visualize the 4-dimensional Iris dataset in 2D space while preserving the most important variance in the data.
# Features
- Loads the Iris dataset from scikit-learn
- Standardizes features using StandardScaler
- Applies PCA to reduce from 4 dimensions to 2 principal components
- Visualizes the transformed data with color-coded species

# Dataset
The Iris dataset contains 150 samples of iris flowers with 4 features:
- Sepal length
- Sepal width
- Petal length
- Petal width
Each sample belongs to one of three species: Setosa, Versicolor, or Virginica.

# Output
The final visualization shows three distinct clusters representing the three Iris species (setosa, versicolor, and virginica) in a reduced 2D feature space.
