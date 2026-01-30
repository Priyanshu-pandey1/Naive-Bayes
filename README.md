# Heart Disease Prediction using Naive Bayes

This project implements a **Gaussian Naive Bayes** classifier to predict the likelihood of heart disease based on clinical patient data. The model is optimized to ensure high sensitivity for medical diagnosis.

## 📌 Project Overview
The goal is to classify patients as either having heart disease or not based on medical features. Naive Bayes is particularly effective for this dataset due to its ability to handle continuous numeric features and provide probabilistic classifications.



## 🛠️ Tech Stack
* **Language:** Python
* **Libraries:** * `Pandas` (Data Processing)
    * `Scikit-Learn` (Machine Learning & Evaluation)

## 📊 Dataset Information
The model uses the `heart.csv` dataset, which contains various patient health metrics.
* **Features (X):** Clinical attributes like age, sex, cholesterol levels, and max heart rate.
* **Target (y):** Heart disease status (1 = Presence, 0 = Absence).

## 📈 Model Performance
The following metrics were calculated using a 20% test split:

| Metric | Score (Decimal) | Score (Percentage) |
| :--- | :--- | :--- |
| **Accuracy** | 0.8524 | **85.25%** |
| **Precision** | 0.8055 | **80.56%** |
| **Recall** | 0.9354 | **93.55%** |



> **Insight:** The model achieved a **Recall of 93.55%**, which is critical in healthcare as it minimizes the risk of missing patients who actually have heart disease (False Negatives).

## 📂 File Structure
* `naive_bayes.ipynb`: Full implementation of the Naive Bayes algorithm.
* `heart.csv`: Dataset used for training and evaluation.
* `README.md`: Project documentation and results.
