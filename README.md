# K-Nearest Neighbors (KNN) - Iris Dataset

## 📌 Task Overview
This project is part of a Data Science Internship task focused on implementing the **K-Nearest Neighbors (KNN)** algorithm using the Iris dataset.

---

## 📊 Dataset
- Dataset Used: **Iris Dataset**
- Features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
- Target:
  - Flower Species (Setosa, Versicolor, Virginica)

---

## ⚙️ Tools & Libraries
- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib / Seaborn

---

## 🚀 Steps Performed

### 1. Data Loading
- Loaded dataset from `sklearn.datasets`

### 2. Data Preprocessing
- Split data into training and testing sets
- Normalized features using StandardScaler

### 3. Model Training
- Used `KNeighborsClassifier` from Scikit-learn
- Selected optimal value of **K**

### 4. Model Evaluation
- Accuracy Score
- Confusion Matrix
- Classification Report

---

## 📈 Results
- Achieved good accuracy on test data
- Observed how different K values affect performance

<img width="1919" height="1018" alt="Task-6" src="https://github.com/user-attachments/assets/b326d952-4f00-4fd4-b39b-298054e16e7e" />

---

## 🔍 Key Learnings
- Understanding of **distance-based algorithms**
- Importance of selecting the right **K value**
- Impact of scaling on KNN performance

---

## ❓ Interview Questions

### What is KNN?
KNN is a supervised machine learning algorithm that classifies data points based on the majority class among its nearest neighbors.

### How to choose K?
- Use cross-validation
- Avoid too small (overfitting) or too large (underfitting)
- Try odd values to avoid ties

---

## 📂 Repository Contents
- `knn_model.py` → Model code
- `dataset/` → Dataset files (if used separately)
- `README.md` → Project documentation

---

## ✅ Conclusion
KNN is a simple yet powerful algorithm for classification tasks. It works well for small datasets and demonstrates the concept of similarity using distance metrics.
