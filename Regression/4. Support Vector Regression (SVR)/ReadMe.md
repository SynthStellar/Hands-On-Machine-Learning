# Support Vector Regression (SVR)

This folder contains an implementation of **Support Vector Regression (SVR)** using Python and Scikit-Learn.

## 📌 Overview
This project demonstrates how to build a **Support Vector Regression** model to predict salaries based on position level. The dataset used is `Position_Salaries.csv`, which consists of the following columns:
1. **Position** (Job Title)
2. **Level** (Position Level - Independent Variable)
3. **Salary** (Dependent Variable - Target)

## 🛠 Libraries Used
- NumPy  
- Pandas  
- Matplotlib  
- Scikit-Learn  

## 🔧 Steps Implemented
1. **Importing the required libraries**
2. **Loading the dataset (`Position_Salaries.csv`)** using Pandas  
3. **Feature Scaling** using StandardScaler from Scikit-Learn  
4. **Training the model** using Support Vector Regression with an RBF kernel  
5. **Making Predictions** for a new position level (6.5)  
6. **Visualizing the SVR results** using Matplotlib  
7. **Creating a high-resolution curve** for a smoother visualization  

## 🚀 How to Run
1. Ensure you have all the required libraries installed (`pip install numpy pandas matplotlib scikit-learn`).
2. Open `support_vector_regression.ipynb` in Jupyter Notebook or [Google Colab](your-colab-link).
3. Run the notebook step by step to train and evaluate the model.

## 📂 Dataset
The dataset (`Position_Salaries.csv`) contains **10 observations** and helps in understanding how Support Vector Regression can model non-linear relationships in data.
