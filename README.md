# Task 6: K-Nearest Neighbors (KNN) Classification 📍

This task focuses on implementing and analyzing the **K-Nearest Neighbors (KNN)** algorithm using the **Iris dataset**. It involves model training, evaluation, hyperparameter tuning, and visualizing performance.

## 🧠 Steps Performed
- Loaded and explored the Iris dataset (`Iris_Species.csv`).
- Encoded categorical labels into numerical format.
- Scaled features using `StandardScaler` for Euclidean distance-based classification.
- Trained a **K-Nearest Neighbors Classifier** using `K=5`.
- Evaluated model using **accuracy**, **confusion matrix**, and **classification report**.
- Experimented with different values of `K` (1–20).
- Plotted **accuracy vs. K** to find the optimal `K`.

## 📊 Results
- **Accuracy (K=5)**: `1.0000`
- **Confusion Matrix** (perfect classification across all 3 classes)
- Classification report confirmed:
  - Precision: `1.00`
  - Recall: `1.00`
  - F1-Score: `1.00`
- Accuracy remained stable at `1.0` for all tested values of `K`.

## 📁 Files
- `Iris_Species.csv` – Raw dataset  
- `KNN_Iris_Classification.ipynb` – Notebook with all modeling, evaluation, and plots

<br>

> 🗓️ Part of internship at Elevate Labs
