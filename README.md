# Classification of Diabetes Using Random Forest Classifier

#### 📌 Overview

The goal of this project was to developed a machine learning model to classify diabetes risk using clinical health data. The project involved exploratory data analysis, outlier handling, feature engineering, and Random Forest classification.

---

#### 🖇️ Datasets

The dataset used in this task is a diabetes dataset sourced from the National Institute of Diabetes
and Digestive and Kidney Diseases (NIDDK). This dataset consists of the following variables:

- **Numeric:** Age, BloodPressure, Glucose, BMI, Insulin, DiabetesPedigreeFunction, Pregnancies, SkinThickness.
- **Target**: Outcome (Non-Diabetes, Diabetes)

The dataset consists of 768 samples, all of which are women aged 21 or older of Pima Indian origin.

**Source:**  A. D. Khare, “Diabetes Dataset,” Kaggle, 2023. [Online]. Available: ****https://www.kaggle.com/datasets/akshaydattatraykhare/diabetes-dataset

---

#### 🌟 What I Did

- Performed exploratory data analysis (EDA) on clinical diabetes dataset
- Detected and handled outliers using IQR method
- Applied feature engineering for BMI and glucose categories
- Built Random Forest classification model
- Evaluated model using accuracy, ROC-AUC, confusion matrix, and feature importance

---

#### ⚙️ Workflow

Exploratory Data Analysis → Outlier Detection (IQR) → Feature Engineering → Train-Test Split (80:20) → Random Forest Training → Model Evaluation → Feature Importance Analysis

---

#### 📊 Results

- The Random Forest model achieved an accuracy of 82%, meaning that out of a total of 154 test data sets, 82% were classified correctly.
- Obtained ROC-AUC score of 0.86, which indicates that the model has excellent classification capabilities.
- Identified glucose, BMI, and age as dominant predictive features

---

#### 📁 Output Visualizations

Classification Report Table

![Classification Report Table](https://github.com/floweredscent/diabetes-classification/blob/main/results/Classification%20Report.png)

Confusion Matrix

![Confusion Matrix](https://github.com/floweredscent/diabetes-classification/blob/main/results/Confusion%20Matrix.png)

ROC Curve 

![ROC Curve ](https://github.com/floweredscent/diabetes-classification/blob/main/results/ROC%20Curve.png)

Feature Importance

![Feature Importance](https://github.com/floweredscent/diabetes-classification/blob/main/results/Feature%20Importance.png)
