# Temporal Stability of Explainable Machine Learning for Disease Activity Prediction in Rheumatoid Arthritis

This repository contains the analysis code supporting my MSc Data Science and Analytics dissertation at Brunel University London.

The study examines the temporal robustness of machine-learning models for predicting subsequent rheumatoid arthritis disease activity and evaluates whether SHAP-based explanations remain stable across temporal patient populations.

## Repository structure

The analysis is organised into three Jupyter notebooks and should be followed in the order below:

1. `01_data_audit_and_preparation.ipynb`  
   Data auditing, preprocessing, construction of next-visit prediction pairs, and preparation of temporal evaluation populations.

2. `02_exploratory_data_analysis.ipynb`  
   Exploratory analysis of cohort characteristics, outcomes, missingness, and predictor distributions.

3. `03_modelling_temporal_evaluation_and_shap.ipynb`  
   Model development and tuning, temporal performance evaluation, distributional-shift analysis, SHAP explanation-stability analysis, and sensitivity analyses.

## Data availability

The analysis uses de-identified data from the Norfolk Arthritis Register (NOAR), obtained under a data-sharing arrangement between Brunel University London and the University of East Anglia.

The underlying NOAR dataset and patient-level derived datasets are not included in this public repository because access is governed by the applicable data-sharing arrangements. Consequently, the notebooks cannot be reproduced from scratch without authorised access to the underlying data.

## Software environment

The final analysis was run using:

- Python 3.14.2
- scikit-learn 1.8.0
- NumPy 2.4.4
- pandas 3.0.2
- SciPy 1.17.1
- XGBoost 3.4.1
- SHAP 0.52.0
- Optuna 4.9.0
- Matplotlib 3.10.8
- joblib 1.5.3

The notebooks retain their analytical outputs so that the results reported in the dissertation can be inspected without access to the restricted dataset.
