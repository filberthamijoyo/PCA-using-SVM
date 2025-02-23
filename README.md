# Dimensionality Reduction Analysis Using SVD/PCA

## Overview
This project demonstrates the application of **Singular Value Decomposition (SVD)** and **Principal Component Analysis (PCA)** to analyze and reduce the dimensionality of the Iris dataset. Key aspects include variance analysis, subspace projection, and reconstruction error evaluation across different dimensions.

## Key Features
1. **Structured Data Splitting**  
   - Class-balanced train-test split (70:30 ratio) while preserving original data order
   - Maintains integrity of class distributions for reliable model evaluation

2. **Feature Engineering**  
   - Standardization of features
   - Label encoding for categorical class labels

3. **Core Analytical Components**  
   - **SVD Decomposition**:
     - Biased covariance matrix calculation (normalized by N)
     - Eigenvalue/eigenvector extraction for variance analysis
   - **Dimensionality Projection**:
     - 1D, 2D, and 3D subspace projections using principal components
     - Data reconstruction from reduced dimensions
   - **Performance Metrics**:
     - Variance retention analysis
     - Mean squared reconstruction error calculation

4. **Visual Analytics**  
   - Interactive plots showing:
     - Variance vs. projection dimension
     - Reconstruction error vs. projection dimension

## Technical Implementation
```python
# Key workflow steps
1. Data preprocessing and standardization
2. Covariance matrix computation
3. SVD decomposition for principal components
4. Projection and reconstruction at different dimensions
5. Variance and error metric calculations
6. Visualization of analytical results
