# heart-disease-ml-pipeline-explainability
End-to-end ML pipeline for heart disease prediction using ensemble learning with SHAP and LIME for model interpretability. 
# machine-learning # healthcare-ai # ensemble-learning # stacking # explainable-ai # shap # lime # mlops # data-science

# ❤️ Heart Disease Prediction with ML Pipeline & Explainable AI

## 📌 Overview

This project presents an end-to-end machine learning pipeline for predicting heart disease using multiple models and ensemble techniques. It integrates Explainable AI methods (SHAP and LIME) to interpret model predictions and enhance transparency.

---

## 🚀 Key Features

* Data preprocessing and feature scaling
* Multiple ML models (Logistic Regression, Random Forest, Gradient Boosting, etc.)
* Stacking ensemble model for improved performance
* K-Fold cross-validation for robustness
* Model evaluation using Accuracy, Precision, ROC-AUC, and Classification Report
* Explainable AI:

  * SHAP (global feature importance)
  * LIME (local prediction explanation)

---

## 🧠 ML Pipeline Workflow

1. Data Loading
2. Exploratory Data Analysis (EDA)
3. Data Preprocessing
4. Model Training (7 ML models)
5. Ensemble Learning (Stacking)
6. Cross-Validation
7. Model Evaluation
8. Explainability (SHAP & LIME)
9. Model Saving

---

## 📊 Results

* Stacking ensemble achieved the best performance across evaluation metrics
* Cross-validation confirms model stability and generalization
* Tree-based models performed consistently well

📌 Detailed results and visualizations are available in the notebook.

---

## 🔍 Explainable AI

### SHAP (Global Interpretation)

* Identifies most influential features affecting predictions
* Provides overall feature importance across dataset

### LIME (Local Interpretation)

* Explains individual predictions
* Helps understand model decisions for specific patients

---

## 📁 Project Structure

```
heart-disease-ml-pipeline-explainability/
│
├── data/
├── notebooks/
│   └── heart_disease_ml_pipeline_explainability.ipynb
├── models/
├── outputs/
├── README.md
├── requirements.txt
```

---

## ⚙️ Installation

```bash
pip install -r requirements.txt
```

---

## ▶️ Usage

Open the notebook:

```bash
notebooks/heart_disease_ml_pipeline_explainability.ipynb
```

Run all cells to:

* Train models
* Evaluate performance
* Generate SHAP and LIME explanations

---

## 📌 Future Improvements

* Deploy model using FastAPI
* Add Docker containerization
* Integrate real-time prediction API
* Extend to federated learning framework

---

## 👩‍💻 Author

Madhuri Dubey
PhD | Machine Learning | Federated Learning | Healthcare AI
