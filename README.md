# B-Cell Lymphoma Microarray Dataset

## Overview
The B-Cell Lymphoma Microarray Dataset is a collection of gene expression data from patients diagnosed with three types of B-cell lymphoma: Diffuse Large B-Cell Lymphoma (DLBCL), Follicular Lymphoma (FL), and Chronic Lymphocytic Leukemia (CLL). Each type of lymphoma presents distinct clinical characteristics and requires specific treatment approaches.

### Classes:
1. **DLBCL (Diffuse Large B-Cell Lymphoma)**
   - Aggressive type of lymphoma.
   - Common and often responds well to chemotherapy.
   - Significant percentage of patients can achieve remission or cure with appropriate treatment.

2. **FL (Follicular Lymphoma)**
   - Usually indolent or slow-growing.
   - Not curable with current treatments, but many patients can live for many years with this condition.
   - Treatments can control the disease, and some individuals may have long periods of remission.

3. **CLL (Chronic Lymphocytic Leukemia)**
   - Type of leukemia closely related to lymphoma, affecting similar white blood cells.
   - Survival rates vary widely, and some patients may not require immediate treatment upon diagnosis.
   - Various treatment options available, and disease progression can be slow in many cases.

## Preprocessing Steps
The dataset has undergone preprocessing to prepare it for analysis. This includes steps such as data cleaning, normalization, and handling missing values.

## Feature Selection
Feature selection techniques have been applied to identify the most relevant attributes or genes for classification or clustering tasks. This helps reduce dimensionality and improve model performance.

## Feature Extraction
Feature extraction methods have been utilized to transform the original features into a lower-dimensional space while preserving essential information. This can aid in capturing underlying patterns and improving computational efficiency.

## Classification Techniques
Various classification algorithms have been employed to predict the type of lymphoma based on gene expression profiles. These include but are not limited to:
- Support Vector Machines (SVM)
- k-Nearest Neighbors (kNN)
- Neural Networks

## Clustering Techniques
Clustering algorithms have been used to group similar samples together based on their gene expression patterns. This can provide insights into the underlying structure of the data and help identify subtypes or clusters within each lymphoma type. Common clustering methods include:
- K-Means Clustering
- Hierarchical Clustering
- Density-Based Clustering (DBSCAN)

## Source

https://www.kaggle.com/datasets/mennaallahsaed/lymphoma

## Contributors

Lymphoma project is made possible by the contributions of the following team members:

- Hager Mohamed - Data Preprocessing +  Data Exploration
- Menna Allah Saed - Classification Techniques + Resampling + Visulaization + Feature Importance
- Reem Ibrahim - Filter Methods (VarianceThreshold + Correlation-based + SelectKBest)
- Aya Ahmed- Wrapper Methods (RFE + Forward Selection)
- Retaj Ayman - Feature Extraction (PCA + Gaussian Random Projection)
- Mohamed Hamdi - Clustering Techniques + Clustering Visualization

## nbviewer link

https://nbviewer.org/github/Menna2002/LymphomaMicroarray/blob/main/lymphoma-notebook.ipynb
