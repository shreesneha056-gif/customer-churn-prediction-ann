# DataScience_MachineLearning----ANN-ModelBuilding----customer_churn_level_prediction_project
## 📝 Project Description
Retaining existing customers is one of the most vital strategies for modern retail banking institutions. This machine learning portfolio project designs, trains, and tunes a deep-learning **Artificial Neural Network (ANN)** script to proactively classify customer churn probabilities based on account balances, credit ratings, geographic positioning, demographics, and product interactions.

To ensure peak deployment stability, the pipeline integrates automated hyperparameter optimization via **Optuna** (`OptunaSearchCV`) combined with `KerasClassifier` wrappers to discover the absolute best combinations of layers, hidden unit weights, and learning speeds.

---

## 🎯 Model Configuration & Performance Summary

The deep learning classifier processes customer features to partition exit outcomes. Below is the primary operational outline of the trained model layer layout:

| Model Pipeline Stage | Technique / Parameter Applied | Objective |
| :--- | :--- | :--- |
| 🧹 **Data Processing** | One-Hot Encoding (Geography/Gender) | Converts qualitative categorizations to binary matrices |
| ⚖️ **Feature Scaling** | Standard Scaler (`StandardScaler`) | Minimizes feature distance weights across loss steps |
| 🧠 **Network Structure** | Dense Neural Architecture (Keras Sequential) | Deep multilayer feature mapping |
| 🚀 **Optimization Engine** | Optuna Automated Trial Search | Scans node metrics to optimize training efficiency |

---

## 🔍 Analytical Observations & Evaluation Metrics

During evaluation, the deep neural network establishes a concrete prediction baseline across historical records:

* **📊 Classification Baseline:** The primary testing datasets report a stable **80% overall accuracy baseline** across classification boundaries.
* **⚠️ Churn Target Nuance:** Due to standard historical imbalances between staying consumers versus leaving segments (a standard characteristic of banking retention ledgers), the model optimizes precision metrics to effectively flags high-risk accounts without triggering costly false-positive alerts.

---

## 🛠️ Tech Stack & Libraries Used
* **Deep Learning Framework:** Keras / TensorFlow Core
* **Hyperparameter Tuning Engine:** Optuna Automation Suite (`optuna-integration`)
* **Scikit-Learn Integration Wrappers:** Scikeras (`KerasClassifier`)
* **Data Pipelines & Matrices:** Pandas, NumPy, Scikit-Learn
* **Visual Representation Layouts:** Matplotlib Engine
* **IDE Workflow Environments:** VS Code / Jupyter Notebooks

---

## 🗂️ Project Repository Structure
```text
├── Data/
│   └── Churn_Modelling.csv             # Raw transactional customer ledger rows
├── Notebooks/
│   └── customer_churn_level_ANN.ipynb # Data scaling, tuning trials, and model script
└── README.md                           # Main structural documentation portfolio
