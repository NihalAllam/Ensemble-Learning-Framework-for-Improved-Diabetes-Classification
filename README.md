# Ensemble-Learning-Framework-for-Improved-Diabetes-Classification
```IMP:``` Code from previous student projects. Using this as a foundation to explore new ideas and develop an improved methodology to achieve better performance.

## Diabetes Classification Using Machine Learning Ensembles
### Overview

This repository contains code and datasets related to a machine learning project on ***diabetes classification*** using multiple preprocessing strategies and classification models.

The work focuses on:

- Handling missing values using different imputation techniques

- Training and evaluating multiple machine learning models

- Comparing performance across datasets and preprocessing methods

This repository mainly serves as a code and experiment archive. It is not intended to be a fully maintained or production-ready project.

### Datasets

The repository uses two datasets:

1. PIMA Indians Diabetes Dataset

A publicly available benchmark dataset

Widely used for diabetes prediction research

Contains medical attributes such as glucose, BMI, insulin, age, etc.

Includes missing or invalid values (often represented as zeros)

2. Local HealthCare Dataset

A secondary dataset used for additional experimentation

Includes similar medical features for diabetes classification

Used to test model behavior beyond a single benchmark dataset

Both datasets are included in CSV format.

Preprocessing and Imputation

Several missing-value handling strategies are explored:

Mean Imputation

Median Imputation

Mode Imputation

Experimental / Proposed Pipeline

Missing values are identified primarily through invalid zero entries in selected medical features.

Each imputation approach is implemented in a separate Jupyter notebook for clarity and comparison.

Models Used

Depending on the notebook, the following machine learning models are evaluated:

Logistic Regression

Decision Tree

Random Forest

Support Vector Machine (SVM)

K-Nearest Neighbors (KNN)

Some experiments also include data scaling and class-imbalance handling techniques.

Repository Structure

*.csv → Dataset files

*-Mean-Imputation.ipynb → Mean imputation experiments

*-Median-Imputation.ipynb → Median imputation experiments

*-Mode-Imputation.ipynb → Mode imputation experiments

*-Proposed-Method.ipynb → Combined / experimental pipeline

Each notebook is self-contained and can be run independently.

Notes

This repository is not actively maintained

Code reflects experimental and academic work

Results may vary depending on environment and library versions

The repository is primarily intended for reference and record-keeping

Disclaimer

This project is for educational and experimental purposes only.
It should not be used for real medical diagnosis or clinical decision-making.
