
# 🔍 Customer Churn Prediction Pipeline (End-to-End ML Project)

This project demonstrates a full-scale machine learning pipeline to predict customer churn using Python, scikit-learn, XGBoost, and MLflow. It includes data ingestion, validation, transformation, model training, evaluation, and deployment via **FastAPI**.

---

## 🚀 Key Features

✅ Modularized ML Pipeline using OOP & Configurations  
✅ Automated Logging via Python's `logging` and `MLflow`  
✅ Baseline model comparison (RandomForest, XGBoost, LogisticRegression, etc.)  
✅ Advanced metrics: Top-Decile Lift, Overfitting Warning  
✅ SHAP-based model explainability  
✅ FastAPI for real-time inference API  

---

## 🛠️ Project Structure

```
Churn_Pred/
├── components/              # Data ingestion, validation, transformation modules
├── entity/                  # Artifact data classes
├── logger/                  # Logging module
├── exception/               # Custom exception handling
├── utils/                   # Utility functions
├── artifacts/               # Outputs: models, reports, metrics
├── app/                     # FastAPI app for deployment
├── main.py                  # Training pipeline entry point
├── mlruns/                  # MLflow tracking
└── README.md
```
---


## 🔁 ML Pipeline Flow

```bash
📦 Data Ingestion → ✅ Validation → 🔄 Transformation → 🔧 Model Training → 📈 Evaluation → 🌐 FastAPI
```

---


