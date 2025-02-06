# Kernel PCA with Logistic Regression

## Prerequisites

### 1. Import Required Libraries
```python
import numpy as np
import matplotlib.pyplot as plt
import pandas as pd
```

### 2. Load Dataset
```python
dataset = pd.read_csv('Wine.csv')
X = dataset.iloc[:, :-1].values
y = dataset.iloc[:, -1].values
```

### 3. Split Dataset into Training and Test Sets
```python
from sklearn.model_selection import train_test_split
X_train, X_test, y_train, y_test = train_test_split(X, y, test_size=0.2, random_state=0)
```

### 4. Apply Feature Scaling
```python
from sklearn.preprocessing import StandardScaler
sc = StandardScaler()
X_train = sc.fit_transform(X_train)
X_test = sc.transform(X_test)
```

### 5. Apply Kernel PCA
```python
from sklearn.decomposition import KernelPCA
kpca = KernelPCA(n_components=2, kernel='rbf')
X_train = kpca.fit_transform(X_train)
X_test = kpca.transform(X_test)
```

### 6. Train Logistic Regression Model
```python
from sklearn.linear_model import LogisticRegression
classifier = LogisticRegression(random_state=0)
classifier.fit(X_train, y_train)
```

### 7. Evaluate Model Performance
```python
from sklearn.metrics import confusion_matrix, accuracy_score
y_pred = classifier.predict(X_test)
cm = confusion_matrix(y_test, y_pred)
accuracy_score(y_test, y_pred)
```

### 8. Visualize Training and Test Set Results
```python
from matplotlib.colors import ListedColormap
# Code to plot decision boundary and scatter points
