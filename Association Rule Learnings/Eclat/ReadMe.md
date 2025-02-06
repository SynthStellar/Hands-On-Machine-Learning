# Eclat Algorithm for Market Basket Analysis

## 📌 Overview  
This project implements the **Eclat Algorithm** for Market Basket Analysis, aimed at finding frequent itemsets and association rules from a dataset of market transactions (`Market_Basket_Optimisation.csv`). Eclat is an efficient method for mining frequent itemsets based on set intersections and is used for association rule mining.

## 🛠 Libraries Used  
- **apyori**: For implementing the Eclat algorithm.
- **NumPy**: For numerical computations.
- **Matplotlib**: For plotting visualizations.
- **Pandas**: For data manipulation and analysis.

## 🔧 Steps Implemented  
1. **Installing and importing necessary libraries**  
2. **Data preprocessing**: Loading the dataset and preparing the transactions for the Eclat algorithm.
3. **Training the Eclat model**: Using the `apyori` library to apply the Eclat algorithm on the transactions.
4. **Visualizing the results**: Displaying the association rules with their supports.

## 🚀 How to Run  
1. Install dependencies using:  
   ```bash
   pip install apyori numpy matplotlib pandas
2. Ensure the dataset (Market_Basket_Optimisation.csv) is available in the same directory as the script.
3. Run the script:
You can execute the script in a Python environment or Jupyter notebook to generate the association rules and insights.