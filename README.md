# Principal Component Analysis and Clustering for Scope 3 Greenhouse Gas (GHG) Emissions Estimation with Hierarchical Linear Modeling

## Introduction & Background

Accurately estimating Scope 3 greenhouse gas (GHG) emissions is challenging due to inconsistent reporting standards, incomplete data, and complex supply chains across diverse industries.

This project implemented Principal Component Analysis (PCA) and Hierarchical Clustering with Hierarchical Linear Modeling (HLM) to determine if accuracy of Scope 3 GHG emissions predictions may be increased.

---

## Problem Statement & Research Question

**Problem Statement:**  
Scope 3 GHG emissions are critical for understanding an organization’s total emissions footprint. However, accurately estimating Scope 3 emissions is difficult because the data is highly complex and often incomplete, due to challenges in collecting and standardizing data across complex supply chains.

**Research Question:**  
Does integrating PCA and hierarchical clustering with HLM modeling improve the accuracy of Scope 3 emissions predictions while still preserving the transparency and interpretability that HLM models offer?

---

## Features

- PCA for dimensionality reduction
- Clustering of companies based on Scope 3 emissions profiles
- HLM modeling for robust emissions estimation

---

## Results

- Most Scope 3 emissions variance is explained by a few key features.
- The optimized HLM model, which utilized company level financial and direct emissions data, was consistently accurate and reliable across all Scope 3 sources.
- Simpler Optimized HLM models outperformed more complex PCA and clustering approaches.
- HLM models demonstrated high predictive power and generalizability across industries.
- Optimized HLM models were more robust for Scope 3 sources with sparse or complex data.

---

## Conclusion & Future Work

- The optimized HLM models can be retrained as new data becomes available to accommodate new information and boost accuracy.
- These results provide a strong foundation for transparent and reliable Scope 3 estimation that can evolve with new data.
