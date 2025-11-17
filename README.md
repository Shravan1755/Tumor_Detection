# 🧬 End-to-End Tumor Detection Project

## 📘 Overview
This project focuses on building a **machine learning model to detect tumor presence** using medical diagnostic data. It covers the full workflow—from importing the dataset to preprocessing, model training, and evaluation—using Python and essential data-science libraries.

## 🔄 Project Workflow

### 📁 Data Loading
* Loaded a tumor dataset containing features such as **cell size**, **texture**, **smoothness**, **compactness**, etc.
* Target variable indicates whether the tumor is **benign** or **malignant**.

### 🧹 Preprocessing
* Handled missing values and cleaned inconsistent records.
* Scaled numerical features for balanced model performance.
* Split data into **training** and **testing** sets.

### 🧠 Model Building
* Implemented machine learning models such as:

  * **Logistic Regression**
  * **Support Vector Machine (SVM)**
  * **Random Forest Classifier**
* Trained models to classify tumor types based on medical features.

### 📊 Evaluation
* Assessed models using:
  * **Accuracy**
  * **Precision**
  * **Recall**
  * **F1-Score**
* Compared model performances to identify the best-performing classifier.

## 📈 Results

| Metric / Insight | Value                                                |
| ---------------- | ---------------------------------------------------- |
| Best Model       | Random Forest / SVM (based on results)               |
| Accuracy         | Strong performance in distinguishing tumor types     |
| Example Insight  | Key features significantly influence tumor diagnosis |

## 🧰 Requirements
```
pip install pandas numpy matplotlib seaborn scikit-learn
```

Run the notebook:
```
jupyter notebook Tumor_detection.ipynb
```
