# Stroke Risk Prediction — Decision Tree, Random Forest, and KNN
**Module:** COMP 30043 Machine Intelligence Systems | Spring 2026

## Project Overview
This project implements and compares three machine learning algorithms — 
Decision Tree, Random Forest (ensemble), and K-Nearest Neighbor — for 
binary stroke risk classification using the Kaggle Stroke Risk Dataset 
(5,110 patient records).

## Dataset
Source: https://www.kaggle.com/datasets/ranaghulamnabi/stroke-risk-dataset

## Files
- stroke_prediction.ipynb — Main Jupyter notebook with all outputs
- stroke_prediction.py — Python script version
- healthcare-dataset-stroke-data.csv — Dataset
- IEEE_Stroke_Report.pdf — Full IEEE research article

## Results Summary
| Metric | Decision Tree | Random Forest | KNN (k=3) |
|--------|--------------|---------------|-----------|
| Accuracy | 75.98% | 76.45% | 83.57% |
| Recall (Stroke) | 63% | 65% | 37% |
| F1-Score | 0.20 | 0.21 | 0.18 |
| AUC | 0.77 | 0.79 | 0.63 |

**Best model: Random Forest** — highest recall, F1-score, and AUC, 
correctly identifying 40 of 62 actual stroke patients in the test set.

## Key Preprocessing Steps
- Median imputation for 201 missing BMI values
- IQR-based outlier capping
- Label encoding for 5 categorical features
- SMOTE oversampling to address 95:5 class imbalance
- StandardScaler normalisation

## How to Run
1. Open stroke_prediction.ipynb in Google Colab
2. Upload healthcare-dataset-stroke-data.csv
3. Run all cells in order
