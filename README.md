# 🌊 Ecosystem Collapse Detection using Machine Learning

This project predicts the likelihood of **ecosystem collapse** based on oceanographic and environmental parameters such as SST (Sea Surface Temperature), pH Level, Bleaching Severity, and more.

We use a variety of machine learning models to analyze which features contribute most significantly to ecological stress and collapse.

---

## 📁 Project Files

- `ModelReview.ipynb`: Core notebook containing full pipeline (preprocessing, model training, feature importance plots, evaluations).
- `ModelReview.pdf`: Exported version of the notebook (good for quick review or submission).
- `dataset.csv`: Input dataset with features like SST, pH, Location, etc.
- `requirement.txt`: Lists all Python dependencies used in this project.

---

## 📊 Models Implemented

- Logistic Regression
- Random Forest Classifier
- Linear Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- XGBoost Classifier

---

## 📈 Outputs

Each model is evaluated using:
- Accuracy
- Precision
- Recall
- F1 Score

Feature importances are visualized using bar charts for each model. A comparative chart across all models is also included.

---

## 📦 Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/ecosystem-collapse-detection.git
   cd ecosystem-collapse-detection
