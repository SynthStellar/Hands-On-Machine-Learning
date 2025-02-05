# Logistic Regression

This folder contains an implementation of **Logistic Regression** using Python and Scikit-Learn.

## 📌 Overview
The **Logistic Regression algorithm** is used for classification, predicting whether a tumor is malignant or benign based on medical attributes. The dataset used is `breast_cancer.csv`, which contains:  
1. **Medical Features** (e.g., mean radius, texture, perimeter, etc.)  
2. **Diagnosis** (Target variable: 1 for malignant, 0 for benign)  

## 🛠 Libraries Used
- Pandas  
- Scikit-Learn  

## 🔧 Steps Implemented
1. **Importing Libraries**  
2. **Loading the dataset (`breast_cancer.csv`)**  
3. **Splitting the dataset** into training and test sets  
4. **Training the Logistic Regression model**  
5. **Making Predictions** for the test set  
6. **Evaluating the model** using the confusion matrix  
7. **Performing k-Fold Cross Validation** to assess model stability  

## 🚀 How to Run
1. Install the required libraries:  
```bash
pip install pandas scikit-learn
2. Ensure breast_cancer.csv is in the working directory.
3. Run the Python script.