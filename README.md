# Diabetes Classification Using Machine Learning Ensembles

## Overview

This repository contains code and datasets related to a machine learning project on diabetes classification using multiple preprocessing strategies and classification models.

The work focuses on:
- Handling missing values using different imputation techniques
- Training and evaluating multiple machine learning models
- Comparing performance across datasets and preprocessing methods

This repository mainly serves as a code and experiment archive. It is not intended to be a fully maintained or production-ready project.

---

## Datasets

The repository uses two datasets:

### 1. PIMA Indians Diabetes Dataset
- Publicly available benchmark dataset
- Widely used in diabetes prediction research
- Contains medical attributes such as glucose, BMI, insulin, age, etc.
- Includes missing or invalid values (often represented as zeros)

### 2. Local HealthCare Dataset
- Secondary dataset used for additional experimentation
- Includes similar medical features for diabetes classification
- Used to evaluate model behavior beyond a single benchmark dataset

Both datasets are included in CSV format.

---

## Preprocessing and Imputation

Multiple missing-value handling strategies are explored:

- Mean Imputation  
- Median Imputation  
- Mode Imputation  
- Experimental / Proposed Pipeline  

Missing values are primarily identified through invalid zero entries in selected medical features.

Each imputation approach is implemented in a separate Jupyter notebook.

---

## Models Used

Depending on the experiment, the following machine learning models are evaluated:

- Logistic Regression  
- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  

Some notebooks also include feature scaling and basic class-imbalance handling.

---

## Repository Structure

- `*.csv` — Dataset files  
- `*-Mean-Imputation.ipynb` — Mean imputation experiments  
- `*-Median-Imputation.ipynb` — Median imputation experiments  
- `*-Mode-Imputation.ipynb` — Mode imputation experiments  
- `*-Proposed-Method.ipynb` — Combined / experimental pipeline  

Each notebook is self-contained and can be executed independently.

---

## Notes

- This repository is not actively maintained
- Code reflects academic and experimental work
- Results may vary depending on environment and library versions
- Intended primarily for reference and archival purposes

---

## Disclaimer

This project is for educational and experimental purposes only.  
It should not be used for real medical diagnosis or clinical decision-making.
