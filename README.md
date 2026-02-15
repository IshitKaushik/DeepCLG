# DeepCLG - Network Intrusion Detection System

This project focuses on detecting network intrusions using machine learning models trained on the UNSW-NB15 dataset.

## Dataset
- Training File: UNSW_NB15_training-set.csv
- Testing File: UNSW_NB15_testing-set.csv

## Models Implemented
1. Logistic Regression (Baseline Model)
2. Random Forest Classifier
3. Tuned Random Forest (RandomizedSearchCV)
4. Extra Trees Classifier (Best Model)

## Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC-AUC Score
- PR-AUC Score

## Folder Structure
- dataset/ : Dataset files
- notebooks/ : Jupyter notebooks for each model
- src/ : Python scripts (optional future use)
- results/ : Output graphs and evaluation reports

## How to Run

### Install dependencies
```bash
pip install -r requirements.txt