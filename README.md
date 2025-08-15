# 🩺 Colorectal Cancer Survival Prediction

![Python](https://img.shields.io/badge/Python-3.10-blue)
![License](https://img.shields.io/badge/License-Academic-lightgrey)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)

## 📚 Table of Contents

- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Dataset Description](#dataset-description)
- [Approach](#approach)
- [Evaluation Metric](#evaluation-metric)
- [Kaggle Submission Format](#kaggle-submission-format)
- [Folder Structure](#folder-structure)
- [Tools & Libraries](#tools--libraries)
- [Author](#author)
- [License](#license)

---

## 📘 Project Overview

Colorectal cancer is the **third most common cancer globally**, posing a significant public health challenge. This project leverages machine learning to **predict the survival outcome** of colorectal cancer patients, aiming to support early diagnosis, personalize treatments, and enhance patient care.

By identifying key predictive factors, we hope to contribute to better **screening strategies** and **treatment planning**, ultimately improving survival rates and resource allocation in healthcare.

---

## ❓ Problem Statement

Develop a machine learning classification model to **predict whether a patient with colorectal cancer is likely to survive**, based on clinical, demographic, and lifestyle features. The target variable is `Survival Prediction`, a binary variable with values `Yes` or `No`.

---

## 🗃️ Dataset Description

You are provided with three datasets:

- `patient_train_data.csv`: Training data with features and survival labels.
- `patient_test_data.csv`: Test data with features only.
- `kaggle_sample_submission.csv`: Sample file for submitting predictions to Kaggle.

**Columns Include:**

- Demographics: `Country`, `Date of Birth`, `Gender`, `Urban or Rural`
- Clinical: `Cancer Stage`, `Tumor Size`, `Diabetes`, `Heart Disease History`
- Lifestyle: `Smoking History`, `Alcohol Consumption`, `Physical Activity`
- Medical Access: `Healthcare Access`, `Insurance Costs`, `Screening History`
- Target Variable: `Survival Prediction`

*(See full column descriptions in the dataset or documentation.)*

---

## ⚙️ Approach

### 🔎 1. Preprocessing & EDA
- Date parsing and age calculation
- Categorical encoding (ordinal and one-hot)
- Missing value treatment
- Class distribution analysis and correlation heatmaps

### 🤖 2. Modeling
- Baseline model (e.g., Logistic Regression)
- Advanced models: Random Forest, Gradient Boosting, and/or XGBoost
- Hyperparameter tuning via cross-validation

### 🧪 3. Evaluation Strategy
- Train-test split or stratified K-fold
- F1-weighted score optimization
- Ensemble strategies or model stacking (optional)

### 💡 4. Additional Insights
- Feature importance ranking
- Partial dependence plots
- Subgroup analysis (e.g., age or cancer stage)

---

## 📏 Evaluation Metric

The competition is evaluated using the **Weighted F1-Score**, which balances both **Precision** and **Recall** across classes and accounts for class imbalance.

---

## 📝 Kaggle Submission Format

The submission file must be a CSV in the following format:

| ID | Survival Prediction |
| --- | --------------- |
| 1 | Yes |
| 2 | No |
| 3 | Yes |

- `ID`: Unique patient identifier  
- `Survival Prediction`: Predicted label (Yes/No)

---

## 🛠️ Tools & Libraries

- Python 3.10
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- Google Colab

---

## 🙋 Author
Name: AbdulQudus Adebogun

Affiliation: NOVA IMS

Email: abdul.adebogun@gmail.com

---

## 📄 License
This project was completed for academic purposes and is shared for educational and portfolio use. Please do not plagiarize or reuse the code without permission or attribution.

---

## 🔗 References
<a href="https://www.kaggle.com/competitions/shaping-the-future-of-cancer/overview">Kaggle Competition Page<a/>

<a href="https://www.who.int/news-room/fact-sheets/detail/cancer">Colorectal Cancer — WHO<a/>

<a href="https://scikit-learn.org/stable/">Scikit-learn Docs<a/>

---
