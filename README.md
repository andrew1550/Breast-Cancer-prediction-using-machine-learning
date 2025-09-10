
# Breast Cancer Prediction

## 📌 Project Overview

**Breast Cancer Prediction** is a **machine learning classification project** aimed at predicting whether a breast mass is **malignant (M)** or **benign (B)**.
The dataset is based on features computed from a **digitized image of a fine needle aspirate (FNA)** of the breast mass. These features describe characteristics of the cell nuclei present in the image.

This project demonstrates how machine learning can be applied in **healthcare and early cancer detection** to support medical decision-making.

---

## 📂 Dataset

The dataset contains:

* **ID number** – Unique identifier for each sample.
* **Diagnosis (Target Variable)** – `M` = Malignant, `B` = Benign.

Each instance also has **10 real-valued features** computed for each cell nucleus:

1. Radius – Mean distance from center to perimeter points.
2. Texture – Standard deviation of gray-scale values.
3. Perimeter – Nucleus perimeter.
4. Area – Nucleus area.
5. Smoothness – Local variation in radius lengths.
6. Compactness – (Perimeter² / Area – 1.0).
7. Concavity – Severity of concave portions of contour.
8. Concave points – Number of concave portions.
9. Symmetry – Symmetry of nucleus.
10. Fractal dimension – "Coastline" approximation (fractal geometry).

---

## 🧠 Machine Learning Approach

* **Data Preprocessing** – Cleaning, feature scaling, and encoding.
* **Exploratory Data Analysis (EDA)** – Visualization of correlations and class distribution.
* **Model Training** – Multiple classification algorithms tested (e.g., Logistic Regression, Random Forest, SVM, etc.).
* **Model Evaluation** – Metrics such as Accuracy, Precision, Recall, F1-score, and ROC-AUC used for performance assessment.

---

## 🚀 Technologies Used

* **Programming Language**: Python 🐍
* **Libraries & Tools**:

  * NumPy, Pandas – Data handling
  * Matplotlib, Seaborn – Data visualization
  * Scikit-learn – Machine learning models and evaluation

---

## 📊 Results

* Achieved high accuracy in distinguishing between **benign** and **malignant** cases.
* Best performing models can be further optimized for **real-world clinical usage**.

---


## 📁 Project Structure

```
breast-cancer-prediction/
│── data/                # Dataset files  
│── notebooks/           # Jupyter notebooks with EDA & model training  
│── models/              # Saved ML models  
│── src/                 # Python scripts for preprocessing & training  
│── README.md            # Project documentation  
```

---

## 🙌 Acknowledgements

Dataset source: **Wisconsin Diagnostic Breast Cancer (WDBC) dataset** – UCI Machine Learning Repository.

---

Would you like me to also **add code snippets** (like how to train and predict) in the README so it looks more practical for recruiters and Kaggle readers?
