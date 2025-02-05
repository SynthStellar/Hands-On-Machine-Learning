# Support Vector Machine (SVM)

This folder contains an implementation of **Support Vector Machine (SVM)** using Python and Scikit-Learn.

## 📌 Overview
The **SVM algorithm** is used for classification, predicting whether a person will purchase a product based on age and estimated salary. The dataset used is `Social_Network_Ads.csv`, which contains:  
1. **Age**  
2. **Estimated Salary**  
3. **Purchased** (Target variable: 1 if purchased, 0 if not)  

## 🛠 Libraries Used
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-Learn  

## 🔧 Steps Implemented
1. **Importing Libraries**  
2. **Loading the dataset (`Social_Network_Ads.csv`)**  
3. **Splitting the dataset** into training and test sets  
4. **Feature Scaling** using StandardScaler  
5. **Training the SVM classifier** with a linear kernel  
6. **Making Predictions** for a new result and the test set  
7. **Evaluating the model** using the confusion matrix and accuracy score  
8. **Visualizing Decision Boundaries** for training and test sets  

## 🚀 How to Run
1. Install the required libraries:  
```bash
pip install numpy pandas matplotlib scikit-learn
2. Ensure Social_Network_Ads.csv is in the working directory.
3. Run the Python script: