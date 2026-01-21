1/22/2026
# CS4630 Learning Activity Q3

## Breast Cancer Wisconsin Diagnostic EDA

### Overview

This assignment performs exploratory data analysis (EDA) on the Breast Cancer Wisconsin Diagnostic dataset from the UCI Machine Learning Repository. The goal is to understand distributions, relationships, and correlation without using the class labels. 

### Dataset

Source: UCI Machine Learning Repository

Link: https://archive.ics.uci.edu/dataset/17/breast+cancer+wisconsin+diagnostic

Observations: 569

Features: ID Number, Diagnosis, 30 continuous variables describing cell nucleus properties

### How to Run

1. Pandas, matplotlib, and seaborn are required.
2. Download `wdbc.data` from the link above.
3. Update the working directory path to your path.
4. Run the notebook

### What the Code Does

- Loads and labels the dataset
- Computes summary statistics using .describe() for six features
- Visualizes features using Kernel Density Estimation plots
- Computes and visualizes a correlation matrix for all features using a heatmap

### Key Findings

- Some distributions are skewed or bimodal
- Multiple features show strong correlations

### Advantages, Limitations, and Future Improvements

- Doing EDA is essential help see relationships and potential patterns between features without using class labels.
  
  - An improvement to this might be comparing the class labels in EDA to see how different features compare for different classes.

- This dataset contains many features that are very similar to one another. 

    - This makes multicollinearity an issue.

    - Feature selection or PCA could be used to pick the features that contribute the most to the target so dimensions are reduced and not redundant.


### Author

Amelia Dennis

CS 4630 - Python for Computational and Data Sciences

Bowling Green State University
