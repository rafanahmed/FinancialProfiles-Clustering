Here’s the clean, concise, emoji-free version of your **README.md**:

---

# CorporateDNA: Clustering Financial Profiles

### Research Question

Can companies be grouped by financial ratios and growth patterns to reveal “high-growth,” “stable,” and “declining” profiles?

---

## Overview

This project applies unsupervised machine learning to cluster public companies based on key financial ratios from income statements, balance sheets, and cash flows. The objective is to uncover natural groupings that reflect different financial behaviors and risk profiles.

---

## Features

* Liquidity: Current Ratio
* Leverage: Debt-to-Equity, Interest Coverage
* Profitability: Net Profit Margin, Return on Assets, Gross Margin
* Efficiency: Asset Turnover
* Cash Flow Strength: Operating Cash Flow Ratio
* Growth: Revenue Growth Rate, Equity Growth Rate

---

## Methods

**Data Source:** Kaggle dataset of public company financial reports (.html tables)
**Processing:** Parse, merge, and normalize ratios per company-quarter
**Models Used:**

* K-Means (baseline clustering)
* Hierarchical Clustering (relationship visualization)
* Gaussian Mixture Model (soft clustering)
  **Evaluation:** Silhouette Score, Calinski-Harabasz Index, PCA/t-SNE visualization

---

## Tech Stack

Python, pandas, numpy, scikit-learn, matplotlib, seaborn, plotly, BeautifulSoup

---

## Workflow

1. Parse and clean financial statements
2. Engineer financial ratios and growth metrics
3. Scale features and perform clustering
4. Visualize and interpret cluster profiles

---

## Results

* Cluster 0: High-Growth – rapid expansion, strong liquidity
* Cluster 1: Stable – steady margins, balanced leverage
* Cluster 2: Declining – weak profits, low coverage

---

## Future Work

Incorporate sector segmentation, add time-series clustering, and build an interactive Streamlit dashboard for visualization.

---
