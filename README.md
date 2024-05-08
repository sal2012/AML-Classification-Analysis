# AML-Classification-Analysis
This repository contains the data and scripts for a project analyzing Acute Myeloid Leukemia (AML) using various clustering and classification techniques to differentiate between AML patients and normal cases.

## Project Description

The project utilizes flow cytometry data consisting of 359 samples with a feature set of 128 markers. The data includes 43 AML cases and 316 normal cases. We address the high dimensionality of the data and imbalance in sample distribution by applying PCA for feature reduction and various clustering methods for exploratory data analysis.

### Clustering Methods Used:
- K-Means Clustering
- Hierarchical Clustering with different linkages (Single, Complete, Ward)

### Classification Techniques:
- Naïve Bayes
- Random Forest
- Decision Tree
- Support Vector Machine (SVM)

## Results

The SVM model showed the highest performance in terms of accuracy and the ability to classify cases without missing any AML cases. Feature importance was further explored using Lasso regression to reduce the number of features without significantly degrading the model performance.
