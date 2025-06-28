# Heart Disease Prediction using Logistic Regression

This repository contains a **Logistic Regression implementation** on the **Cleveland Heart Disease dataset** using Python and `scikit-learn` to predict the presence of heart disease based on medical and demographic features.

---

## ❤️ What is Logistic Regression?

**Logistic Regression**:
- Is a supervised classification algorithm used for **binary or multiclass classification**.
- Estimates the probability that a given input point belongs to a certain class using the logistic (sigmoid) function.
- Outputs values between 0 and 1, which can be thresholded to assign class labels.

In this project:
- **Target = 1:** Heart disease present.
- **Target = 0:** No heart disease.

---

## 🚀 Features

✅ Loads the **Cleveland Heart Disease dataset**.  
✅ Splits data into **features (`X`) and target (`y`)**.  
✅ Uses a **70%-30% train-test split** for evaluation.  
✅ Trains a **Logistic Regression classifier** using `scikit-learn`.  
✅ Evaluates the model using:
- **Precision**
- **Recall**
- **Accuracy**
- **Confusion Matrix**

---

## 🗂️ Dataset

The **Cleveland Heart Disease dataset** contains:
- **Features:** 
  - Age, sex, chest pain type, resting blood pressure, cholesterol, fasting blood sugar, resting ECG, max heart rate, exercise-induced angina, ST depression, slope, number of major vessels, and thalassemia.
- **Target:**
  - 0: No heart disease.
  - 1: Heart disease present.

The dataset is typically used for **binary classification in medical machine learning applications**.

---

## 🛠️ Dependencies

- Python 3.x
- pandas
- numpy
- scikit-learn

Install dependencies using:

```bash
pip install pandas numpy scikit-learn
