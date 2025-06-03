# Task-6-K-Nearest-Neighbors-KNN-Classification
K-Nearest Neighbors (KNN) Classification

## 🎯 Objective
To understand and implement K-Nearest Neighbors (KNN) for classification using the breast cancer dataset. This task explores model evaluation across different K values and visualizes decision boundaries.

## 🧰 Tools Used
- Python
- Pandas
- scikit-learn
- Matplotlib

## 📊 Dataset
- **Source**: `sklearn.datasets.load_breast_cancer()`
- **Features**: 30 real-valued input features
- **Target**: Binary classification - `0` (malignant), `1` (benign)

## 🧪 Steps Performed
1. **Data Loading & Preprocessing**
   - Loaded the dataset and normalized features using `StandardScaler`.

2. **Train-Test Split**
   - Split the dataset into 70% training and 30% testing using `train_test_split`.

3. **KNN Classification**
   - Trained multiple KNN models using `KNeighborsClassifier` with varying values of K (1 to 10).
   - Evaluated each model's accuracy.

4. **Model Evaluation**
   - Identified the best K based on accuracy.
   - Evaluated final model using:
     - Accuracy
     - Confusion Matrix
     - Classification Report

5. **Visualization**
   - Plotted accuracy vs K to select optimal K.
   - Created decision boundary plot using first two features for visual understanding.

## 📈 Key Visuals
- `knn_accuracy_vs_k.png` - Shows how accuracy changes with K.
- `knn_decision_boundary.png` - Displays decision boundaries with 2D feature projection.

## 🧠 Insights
- KNN performance is sensitive to the value of K.
- Normalization is crucial for distance-based algorithms.
- Decision boundaries offer intuition behind classification behavior.

## 📁 Files
- `knn_classification.py` – Complete implementation
- `knn_accuracy_vs_k.png` – Accuracy vs K plot
- `knn_decision_boundary.png` – Decision boundary visualization

## ✅ Results
- Achieved high accuracy with K=5 (or best K found).
- Model shows robust performance on test set with clear decision boundaries.

**End of Task 6**
