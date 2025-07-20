# Ecosystem Collapse Detection using ML

This project explores the prediction of ecosystem collapse based on oceanic and ecological parameters like Sea Surface Temperature (SST), pH Level, Bleaching Severity, etc., using machine learning models including:

- Logistic Regression
- Random Forest
- Linear SVM
- KNN
- XGBoost

## 📊 Features
- Dataset preprocessing and label encoding
- Binary classification (`Collapse` = species observed < 100)
- Model training and feature importance extraction
- Accuracy, Precision, Recall, F1 Score metrics for evaluation
- Model comparison across various feature combinations

## 📁 Files
- `ModelReview.ipynb`: All code and outputs in notebook format
- `data/dataset.csv`: Input dataset (anonymized)
- `results/`: Evaluation metrics
- `plots/`: Feature importance visuals

## 🧪 Dependencies
Install required packages:
```bash
pip install -r requirements.txt
