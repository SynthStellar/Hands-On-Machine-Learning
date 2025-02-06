# Kernel SVM

This folder contains an implementation of **Kernel SVM (Support Vector Machine)** using Python and Scikit-Learn.

## 📌 Overview
This project demonstrates how to build a **Kernel SVM** model to predict whether a person will purchase a product based on age and estimated salary. The dataset used is `Social_Network_Ads.csv`, which includes:
1. **Age**  
2. **Estimated Salary**  
3. **Purchased** (Target variable: 1 if purchased, 0 if not)

## 🛠 Libraries Used
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-Learn  

## 🔧 Steps Implemented
1. **Importing the required libraries**  
2. **Loading the dataset (`Social_Network_Ads.csv`)** using Pandas  
3. **Splitting the dataset** into training and test sets  
4. **Feature Scaling**  
5. **Training the Kernel SVM model** using the RBF kernel  
6. **Making Predictions** for a new result and the test set  
7. **Evaluating the model** using the confusion matrix and accuracy score  
8. **Visualizing the results** for both training and test sets  

## 🚀 How to Run
1. Ensure `Social_Network_Ads.csv` is present in the working directory.  
2. Install the required libraries if not already installed:  
   ```bash
   pip install numpy pandas matplotlib scikit-learn
3. Run the Python script using:
python kernel_svm.py
or execute the code in a Jupyter Notebook.
## 📂 Dataset  
The dataset (`Social_Network_Ads.csv`) contains data about users' **age**, **estimated salary**, and whether they **purchased** a product (target variable: `1` if purchased, `0` if not).