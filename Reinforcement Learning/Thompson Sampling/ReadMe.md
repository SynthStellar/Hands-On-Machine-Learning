# Thompson Sampling - Ad Selection Optimization

## Prerequisites

Before running the script, ensure you have the following libraries installed:

```bash
pip install numpy pandas matplotlib
```

## Dataset

The script uses a dataset named `Ads_CTR_Optimisation.csv`. Ensure the dataset is in the same directory as the script.

## Description

The script implements the Thompson Sampling algorithm to optimize ad selection based on click-through rates (CTR). It includes:
- Initializing parameters for Bayesian updating
- Iterating over multiple rounds to update reward distributions
- Selecting ads based on Beta distributions
- Visualizing the selection frequency of each ad using a histogram

Run the script to analyze ad performance and optimize ad selection strategy dynamically.
