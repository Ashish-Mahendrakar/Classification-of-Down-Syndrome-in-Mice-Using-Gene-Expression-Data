# Classification-of-Down-Syndrome-in-Mice-Using-Gene-Expression-Data


## Overview

This project focuses on predicting Down syndrome in mice based on gene expression variables. The task is to classify the genotype (binary) using gene expression data from various genes. The project includes data exploration, preprocessing, model training, and feature selection.

## Dataset

The dataset can be downloaded from the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Mice+Protein+Expression). The dataset contains gene expression values and information for predicting the genotype of mice.

## Project Structure

- **Data Exploration and Pre-processing**: Notebook for exploring, visualizing, and pre-processing the data. Includes handling missing values using multivariate feature imputation.
- **Model Training and Validation**: Notebook for training, validating (with hyperparameter tuning), and testing the following models:
  - Random Forest
  - Support Vector Classification with RBF Kernel
- **Feature Selection**: Notebook for applying recursive feature elimination to evaluate if removing certain features improves model performance.

## Steps Completed

1. **Data Exploration and Pre-processing**
   - Downloaded the dataset for predicting Down syndrome in mice.
   - Explored and visualized the data to understand its characteristics.
   - Pre-processed the data, including handling missing values with multivariate feature imputation as described in [scikit-learn's documentation](https://scikit-learn.org/stable/modules/impute.html).

2. **Model Training and Validation**
   - Trained and validated the following models:
     - Random Forest
     - Support Vector Classification with RBF Kernel
   - Varied at least one hyperparameter for model validation.

3. **Feature Selection**
   - Applied recursive feature elimination using [scikit-learn's RFECV](https://scikit-learn.org/stable/modules/generated/sklearn.feature_selection.RFECV.html) to assess if removing features improves model performance.


## Results and Findings

- The models were evaluated based on their performance metrics.
- The impact of feature removal on model performance was analyzed using recursive feature elimination.
- Insights were gained into the importance of different features for predicting Down syndrome in mice.

## Contributing

Contributions to enhance the analysis or add new features are welcome. Please submit issues or pull requests as needed.

