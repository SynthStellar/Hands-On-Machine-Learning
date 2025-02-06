# Apriori Algorithm for Market Basket Analysis

## 📌 Overview  
This project implements the **Apriori Algorithm** for Market Basket Analysis to find frequent itemsets and association rules from a dataset of market transactions (`Market_Basket_Optimisation.csv`). The goal is to uncover patterns in the dataset and extract insights such as which items are often bought together.

## 🛠 Libraries Used  
- **apyori**: For implementing the Apriori algorithm.
- **NumPy**: For numerical computations.
- **Matplotlib**: For plotting visualizations.
- **Pandas**: For data manipulation and analysis.

## 🔧 Steps Implemented  
1. **Installing and importing necessary libraries**  
2. **Data preprocessing**: Loading the dataset and preparing the transactions for the Apriori algorithm.
3. **Training the Apriori model**: Using the `apyori` library to apply the Apriori algorithm on the transactions.
4. **Visualizing the results**: Displaying the association rules, supports, confidences, and lifts in a well-organized manner.

## 🚀 How to Run  
1. Install dependencies using:  
   ```bash
  pip install apyori numpy matplotlib pandas
  
2. Ensure the dataset (Market_Basket_Optimisation.csv) is available in the same directory as the script.
3. Run the script:
You can execute the script in a Python environment or Jupyter notebook to generate the association rules and insights.