# 🩺 PCOS Prediction Using Machine Learning with SHAP & LIME Explainability

## 📌 Overview
This project predicts whether a patient has **Polycystic Ovary Syndrome (PCOS)** using clinical and hormonal features.  
Multiple machine learning models were trained and compared, and explainability techniques **SHAP** and **LIME** were integrated to understand *why* the model makes certain predictions.

This improves trust, transparency, and interpretability for real-world medical use.

---

## 🚀 Features
- ✔ Multiple ML models trained (RF, LR, SVM, KNN, Decision Tree, Gradient Boosting)  
- ✔ SHAP global feature importance  
- ✔ LIME local patient-level interpretation  
- ✔ Clean prediction pipeline  
- ✔ Saved models for reuse  
- ✔ Easy-to-run notebook  

---

## 📂 Project Structure
PCOS-Prediction-Explainability/
│
├── README.md
├── LICENSE
├── requirements.txt
├── pcos-with-lime-and-shap.ipynb
│
├── models/
│ ├── rf_model.pkl
│ ├── imputer.pkl
│ └── feature_names.pkl
│
└── images/
├── shap_summary_plot.png
├── lime_example.png
└── model_accuracy_comparison.png

---

## 🧪 Machine Learning Models Used
- **Logistic Regression**
- **Random Forest Classifier** (main model for SHAP)
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**
- **Decision Tree**
- **Gradient Boosting**

Each model is trained and evaluated to compare performance.

---

## 🧠 Explainability Methods

### 🔍 SHAP (SHapley Additive exPlanations)
- Shows how each feature contributes to the model prediction  
- Helps identify top PCOS indicators  
- Used for **global explainability**  
- Applied mainly on **Random Forest**

### 🔎 LIME (Local Interpretable Model-Agnostic Explanations)
- Explains *one specific prediction*  
- Shows which features increased/decreased PCOS probability  
- Helps doctors with case-by-case understanding

---

## 📁 Dataset
The dataset includes:
- Clinical details (Age, BMI, Cycle length, etc.)  
- Hormonal levels (AMH, FSH, LH, etc.)  
- Ultrasound features (Follicle count)  
- Target variable:  
  - **0 → No PCOS**  
  - **1 → PCOS**

(*Dataset may not be uploaded due to privacy; users can add their own dataset in a `data/` folder.*)

---

## 🛠 Installation

