# 🧬 Diabetes Disease Prediction with Logistic Regression and SVM


## 📌 Project Overview
This project focuses on **diabetes disease prediction** using the **Diabetes Dataset**.

Two machine learning classification models are implemented and compared:
-  Logistic Regression
-  Support Vector Machine (SVM)

The models are evaluated using **Accuracy, Precision, Recall/Sensitivity, F1-Score, and Specificity**.


## 🧬 Dataset
**Dataset:** Diabetes Dataset
**Source:** Scikit-learn Built-in Dataset

- **Samples:** 442
- **Features:** 10 numerical features
- **Classification:** Binary Classification
- **0 → Not Diabetes**
- **1 → Diabetes**
  
The features represent baseline patient measurements — age, sex, BMI, average blood pressure, and six blood serum values — and the target is derived from a one-year disease progression score, split at the median to create a binary label.

## ⚙️ Workflow

🔹 Load dataset directly from `sklearn.datasets`
🔹 Split data into training and testing sets
🔹 Scale features using `StandardScaler`
🔹 Train Logistic Regression and SVM (RBF kernel) classifiers
🔹 Evaluate with confusion matrix, ROC curve, and classification metrics

---

## 📚 Scikit-learn


## Machine Learning Tasks

### 1. Classification
→ Identifying which category an object belongs to.

**Applications:** Spam detection, image recognition  
**Algorithms:** Gradient Boosting, Nearest Neighbors, Random Forest, Logistic Regression

### 2. Regression
→ Predicting a continuous-valued attribute associated with an object.

**Applications:** Drug response, stock price prediction  
**Algorithms:** Gradient Boosting, Nearest Neighbors, Random Forest, Ridge Regression

### 3. Clustering
→ Automatic grouping of similar objects into sets.

**Applications:** Customer segmentation, grouping experiment outcomes  
**Algorithms:** k-Means, HDBSCAN, Hierarchical Clustering

### 4. Dimensionality Reduction
→ Reducing the number of random variables to consider.

**Applications:** Data visualization, increased efficiency  
**Algorithms:** Principal Component Analysis (PCA), Feature Selection, Non-Negative Matrix Factorization (NMF)

### 5. Model Selection
→ Comparing, validating, and choosing the best parameters and models.

**Applications:** Improved model accuracy through parameter tuning  
**Algorithms/Techniques:** Grid Search, Cross-Validation, Performance Metrics

### 6. Preprocessing
→ Feature extraction and normalization of input data.

**Applications:** Transforming input data, such as text, for use with machine learning algorithms  
**Techniques:** Data Preprocessing, Feature Extraction



## 📏 Evaluation Metrics

For classification tasks, evaluation metrics include accuracy, precision, recall, F1-score, and area under the ROC curve (AUC-ROC).
- **Accuracy:** Measures the proportion of correct predictions out of total predictions.
- **Precision:** Focuses on positive predictions, quantifying how many selected items are relevant.
- **Recall:** Also known as sensitivity, recall evaluates the model's ability to find all the relevant instances.
- **F1-score:** The harmonic mean of precision and recall, providing a balance between these two metrics.
- **AUC-ROC:** A metric for assessing the performance of a classification model where the output is a probability. It visually represents the tradeoff between the true positive rate (TPR) and false positive rate (FPR).

For regression tasks, common evaluation metrics in scikit-learn include mean absolute error (MAE), root mean squared error (RMSE), R2 score, and mean squared error (MSE).
- **MAE:** Measures the average magnitude of errors without considering their direction.
- **RMSE:** The square root of the mean of squared errors, giving more weight to larger errors.
- **R2 score:** Also known as coefficient of determination, this score represents the proportion of the variance in the dependent variable that is predictable from the independent variables.
- **MSE:** Calculates the average squared difference between the predicted and actual values, offering a measure of how close fits are to the data points.



