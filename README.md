# Breast-Cancer-Prediction

## Project Overview

This project uses Machine Learning to predict whether a breast tumor is **Benign** or **Malignant** using the Breast Cancer Wisconsin Dataset available in Scikit-learn.

The model is built using a **Support Vector Machine (SVM)** classifier and trained on 30 medical features extracted from breast cancer cell images.

---

## Dataset Information

* **Dataset:** Breast Cancer Wisconsin Dataset
* **Source:** Scikit-learn (`load_breast_cancer()`)
* **Total Samples:** 569
* **Features:** 30
* **Target Classes:**

  * 0 = Malignant
  * 1 = Benign

### Class Distribution

* Malignant: 212
* Benign: 357

---

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn

---

## Project Workflow

1. Import required libraries
2. Load Breast Cancer dataset
3. Create a Pandas DataFrame
4. Perform Exploratory Data Analysis (EDA)
5. Visualize feature relationships using Pairplots
6. Split dataset into Training and Testing sets
7. Train SVM (SVC) model
8. Make predictions on test data
9. Evaluate model using:

   * Confusion Matrix
   * Classification Report

---

## Features Used

Some important features include:

* Radius
* Texture
* Perimeter
* Area
* Smoothness
* Compactness
* Concavity
* Concave Points
* Symmetry
* Fractal Dimension

---

## Model

The project uses the **Support Vector Classifier (SVC)** from Scikit-learn:

```python
from sklearn.svm import SVC

model = SVC()
model.fit(X_train, y_train)
```

---

## Evaluation Metrics

The model performance is evaluated using:

- Confusion Matrix
- Classification Report
  - Precision
  - Recall
  - F1-Score
  - Accuracy

---

## Objective

To build a machine learning model that can accurately classify breast tumors as **Benign** or **Malignant** based on medical measurements.


