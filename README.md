# 📉 Customer Churn Prediction using ANN

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=flat-square&logo=keras&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![Optuna](https://img.shields.io/badge/Optuna-Hyperparameter%20Tuning-blue?style=flat-square)
![Accuracy](https://img.shields.io/badge/Accuracy-86%25-brightgreen?style=flat-square)

> Deep learning ANN model to predict at-risk customers, enabling proactive retention strategies for telecom and banking businesses.

---

## 📌 Problem Statement
Customer churn is a costly problem — acquiring a new customer costs 5x more than retaining an existing one. This project builds a binary classification ANN to identify customers likely to churn, allowing businesses to intervene with targeted offers before they leave.

## 🎯 Results

| Metric | Score |
|--------|-------|
| **Accuracy** | **86%** |
| Precision | 84% |
| Recall | 83% |
| F1-Score | 83% |
| Model | Sequential ANN (Keras) |
| Hyperparameter Tuning | Optuna (OptunaSearchCV) |
| Task | Binary Classification |

## 🛠️ Tech Stack
- **Language:** Python
- **Deep Learning:** Keras, TensorFlow
- **Hyperparameter Tuning:** Optuna
- **Data Processing:** Pandas, NumPy, Scikit-learn
- **Visualization:** Matplotlib, Seaborn
- **Environment:** Jupyter Notebook

## 📂 Project Structure
```
customer-churn-prediction-ann/
├── data/          # Customer dataset
├── python/        # Jupyter notebooks & scripts
├── requirements.txt
└── README.md
```

## 🚀 How to Run
```bash
git clone https://github.com/shreesneha056-gif/customer-churn-prediction-ann.git
cd customer-churn-prediction-ann
pip install -r requirements.txt
jupyter notebook
```

## 📊 Pipeline Overview
1. **Data Loading & EDA** — Explore customer features (balance, credit score, geography, product usage)
2. **Preprocessing** — Encode categoricals, StandardScaler normalization
3. **ANN Model Building** — Sequential: Dense → BatchNorm → Dropout layers
4. **Hyperparameter Tuning** — Optuna OptunaSearchCV for optimal layers/neurons/lr
5. **Evaluation** — Accuracy 86%, Precision 84%, Recall 83%, F1 83%
6. **Business Insight** — Identified ~20% high-risk customer segment for retention campaigns

---
📫 [LinkedIn](https://www.linkedin.com/in/sneha-shree-mu/) | [Portfolio](https://shreesneha056-gif.github.io/portfolio_website/) | [GitHub](https://github.com/shreesneha056-gif)
