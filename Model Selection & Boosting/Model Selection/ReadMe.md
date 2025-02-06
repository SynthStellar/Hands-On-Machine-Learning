# Kernel SVM with Grid Search and k-Fold Cross Validation

This project demonstrates the use of the Kernel Support Vector Machine (SVM) for classifying data from the `Social_Network_Ads.csv` dataset. It involves two key components:
1. **Kernel SVM with Grid Search**: Optimizing hyperparameters (such as `C` and `gamma`) using Grid Search to find the best model.
2. **k-Fold Cross Validation**: Evaluating the model’s performance across different subsets of the training data to estimate its generalization capability.

The steps include:
- **Dataset Import and Preprocessing**: Load the dataset, split it into training and testing sets, and scale the features.
- **Model Training**: Train a Kernel SVM model using the `rbf` (Radial Basis Function) kernel.
- **Hyperparameter Tuning with Grid Search**: Find the best hyperparameters for the Kernel SVM.
- **Model Evaluation**: Evaluate the model using a confusion matrix, accuracy score, and k-Fold Cross Validation.
- **Visualization**: Visualize the decision boundaries of the SVM model on both the training and test sets.

## Prerequisites

To run this project, you need to have the following Python libraries installed:

### Required Libraries

- **NumPy**: For numerical operations and handling arrays.
- **Matplotlib**: For plotting and visualizing data.
- **Pandas**: For data manipulation and analysis.
- **Scikit-learn**: For machine learning models, including SVM and cross-validation.

### Installation

You can install the required libraries by running the following command in your terminal:

```bash
pip install numpy matplotlib pandas scikit-learn
