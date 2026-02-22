# Heart Disease Decision Tree 
# Heart Disease Decision Tree

## 📖 Project Overview
This project demonstrates **Decision Tree classification** on the Heart Disease dataset. The goal is to predict whether a patient has heart disease based on various medical attributes using **Decision Tree** and optionally **Random Forest** algorithms.

---

## 📊 Dataset
- The dataset used is `heart.csv`.
- It contains several features like:
  - Age
  - Sex
  - Chest pain type
  - Resting blood pressure
  - Cholesterol
  - Fasting blood sugar
  - Resting ECG results
  - Maximum heart rate achieved
  - Exercise induced angina
  - ST depression induced by exercise
  - Slope of the ST segment
  - Number of major vessels
  - Thalassemia
- Target column: `target` (0 = No Disease, 1 = Disease)

---

## 🛠 Libraries Used
- `pandas` – data manipulation
- `scikit-learn` – train/test split, Decision Tree, Random Forest, evaluation
- `graphviz` – visualize Decision Tree

Install libraries (if not already installed):

```bash
pip install pandas scikit-learn graphviz
