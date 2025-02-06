# Upper Confidence Bound (UCB) - Ad Selection Optimization

## Prerequisites

Before running the script, ensure you have the following libraries installed:

```bash
pip install numpy pandas matplotlib
```

## Dataset

The script uses a dataset named `Ads_CTR_Optimisation.csv`. Ensure the dataset is in the same directory as the script.

## Description

The script implements the Upper Confidence Bound (UCB) algorithm to optimize ad selection based on click-through rates (CTR). It includes:
- Initializing parameters for selection counts and rewards
- Iterating over multiple rounds to update confidence bounds
- Selecting ads based on the UCB formula
- Visualizing the selection frequency of each ad using a histogram

Run the script to analyze ad performance and optimize ad selection strategy dynamically.
