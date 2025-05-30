# Logistic Regression - Haberman's Survival Dataset

This project demonstrates the use of **Logistic Regression** to build a binary classifier on **Haberman’s Survival Dataset**.

## 🎯 Objective
To predict whether a patient survived 5 or more years after undergoing surgery for breast cancer.

## 🧰 Tools & Libraries Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## 📁 Dataset
- **Source**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/haberman%27s+survival)
- **Features**:
  - Age of patient at time of operation
  - Patient's year of operation (year - 1900)
  - Number of positive axillary nodes detected
- **Target**:
  - 1 = Survived 5+ years
  - 2 = Died within 5 years

## 🚀 Project Steps

### 1. Load Dataset
Download the data and load it into a DataFrame.

### 2. Preprocess
- Convert the target column into binary (1 for survived, 0 for died).
- Split data into training and test sets.
- Standardize features.

### 3. Train Logistic Regression Model
Train a logistic regression model using scikit-learn.

### 4. Evaluation
- Confusion matrix
- Classification report (precision, recall, F1-score)
- ROC-AUC score
- ROC Curve visualization

### 5. Bonus: Sigmoid Function Plot
Visualize the sigmoid function used in logistic regression.

## 📊 Results
Evaluate how well the model distinguishes between the two classes using ROC-AUC and other metrics.

## 📝 License
This project is open-source and available for educational use.

---
