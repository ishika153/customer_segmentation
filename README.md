# E-Commerce Customer Segmentation

## Overview
This project uses RFM analysis and unsupervised machine learning to segment e-commerce customers based on their purchasing behaviour.

## Dataset
**UCI Online Retail Dataset:** https://archive.ics.uci.edu/dataset/352/online+retail

## Objectives
- Calculate Recency, Frequency, and Monetary (RFM) values.
- Apply K-Means and DBSCAN clustering.
- Visualize customer segments using PCA and t-SNE.
- Derive marketing personas from customer clusters.

## Technologies Used
Python, Pandas, NumPy, Matplotlib, Scikit-learn, Jupyter Notebook.

## Workflow
1. Explore and clean transaction data.
2. Calculate customer-level RFM features.
3. Scale features using `StandardScaler`.
4. Apply K-Means and DBSCAN.
5. Visualize clusters using PCA and t-SNE.
6. Interpret clusters and assign marketing personas.

## How to Run
1. Download the dataset from the link above.
2. Place `Online Retail.xlsx` in the notebook folder.
3. Install dependencies:

   ```bash
   pip install numpy pandas matplotlib scikit-learn openpyxl
   ```

4. Open the Jupyter Notebook and run all cells.

## Outcome
Identify customer segments, visualize purchasing patterns, and derive simple marketing strategies for different customer groups.
