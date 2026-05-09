# Stroke Risk Prediction — Decision Tree and KNN
**Module:** COMP 30043 Machine Intelligence Systems | Spring 2026

## Project Overview
This project implements and compares Decision Tree and K-Nearest Neighbor 
algorithms for binary stroke risk classification using the Kaggle Stroke 
Risk Dataset (5,110 patient records).

## Dataset
Source: https://www.kaggle.com/datasets/ranaghulamnabi/stroke-risk-dataset

## Files
- stroke_prediction.ipynb — Main Jupyter notebook with all outputs
- stroke_prediction.py — Python script version
- healthcare-dataset-stroke-data.csv — Dataset
- IEEE_Stroke_Report.pdf — Full IEEE research article

## Results Summary
| Metric | Decision Tree | KNN (k=3) |
|--------|--------------|-----------|
| Accuracy | 75.98% | 83.57% |
| Recall (Stroke) | 63% | 37% |
| F1-Score | 0.20 | 0.18 |
| AUC | 0.77 | 0.63 |

## How to Run
1. Open stroke_prediction.ipynb in Google Colab
2. Upload the CSV file
3. Run all cells in order
