# Natural Language Processing - Restaurant Reviews Classification

## Prerequisites

Before running the script, ensure you have the following libraries installed:

```bash
pip install numpy pandas matplotlib nltk scikit-learn
```

Additionally, you need to download the NLTK stopwords dataset:

```python
import nltk
nltk.download('stopwords')
```

## Dataset

The script uses a dataset named `Restaurant_Reviews.tsv`. Ensure the dataset is in the same directory as the script.

## Description

The script performs sentiment analysis on restaurant reviews using Natural Language Processing (NLP). It includes:
- Text preprocessing (cleaning, stemming, and stopword removal)
- Bag of Words (BoW) feature extraction
- Splitting data into training and testing sets
- Training a Naive Bayes classifier
- Evaluating model performance using accuracy score and confusion matrix

Run the script to preprocess text data, train a model, and predict sentiments of restaurant reviews.
