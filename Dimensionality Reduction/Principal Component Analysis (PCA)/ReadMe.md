# Principal Component Analysis (PCA) - Prerequisites

## Requirements
Ensure you have the following installed:

- Python 3.x
- NumPy
- Pandas
- Matplotlib
- scikit-learn

## Installation
Run the following command to install required packages:
```sh
pip install numpy pandas matplotlib scikit-learn
```

## Dataset
- The script uses a dataset named `Wine.csv`. Ensure this dataset is available in the working directory.

## Steps Covered
1. Import necessary libraries.
2. Load and preprocess the dataset.
3. Split the dataset into training and test sets.
4. Perform feature scaling.
5. Apply Principal Component Analysis (PCA).
6. Train a Logistic Regression model.
7. Evaluate the model using a confusion matrix and accuracy score.
8. Visualize training and test set results.

## Notes
- PCA reduces the dimensionality of the dataset while preserving variance.
- The number of principal components used in this implementation is 2 (`n_components=2`).
- Ensure proper preprocessing (e.g., scaling) before applying PCA for optimal performance.

## Usage
Run the script using:
```sh
python script_name.py