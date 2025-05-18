# Customer Segmentation with K-Means Clustering

## Overview

This project applies K-Means clustering to segment customers based on their age, annual income, and spending score using the Mall Customers dataset. The goal is to identify distinct customer groups to help the mall better understand its clientele and tailor marketing strategies.

## Dataset

- **Source:** [Mall Customer Segmentation Data by vjchoudhary7 on Kaggle](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)
- **Filename:** `Mall_Customers.csv`

## How to Run

1. Open the project folder in VS Code.
2. Open the Jupyter notebook file: `customer_segmentation.ipynb`.
3. Run all cells in order. Make sure you have the required libraries installed:
   - pandas
   - numpy
   - matplotlib
   - seaborn
   - scikit-learn

You can install any missing libraries using:
pip install pandas numpy matplotlib seaborn scikit-learn


## Project Steps

1. **Data Loading & Exploration:** Loaded and explored the Mall Customers dataset.
2. **Data Cleaning:** Checked for missing values and selected relevant features (`Age`, `Annual Income (k$)`, `Spending Score (1-100)`).
3. **Visualization:** Used pairplots and scatterplots to visualize relationships between features.
4. **Clustering:** Applied K-Means clustering and used the Elbow Method to determine the optimal number of clusters.
5. **Interpretation:** Analyzed and interpreted the resulting customer segments.

## Cluster Interpretation

- **Cluster 0:**  
  Average Age: ~46  
  Average Annual Income: ~$48,000  
  Average Spending Score: ~42  
  *Older customers with moderate income and average spending behavior. Likely represent mature consumers with balanced purchasing habits.*

- **Cluster 1:**  
  Average Age: ~32  
  Average Annual Income: ~$108,000  
  Average Spending Score: ~83  
  *Young, high-income, high-spending customers. Likely the most valuable segment for the mall.*

- **Cluster 2:**  
  Average Age: ~25  
  Average Annual Income: ~$30,000  
  Average Spending Score: ~74  
  *Very young customers with low income but high spending. Possibly students or young professionals who spend significantly relative to their earnings.*

- **Cluster 3:**  
  Average Age: ~40  
  Average Annual Income: ~$87,000  
  Average Spending Score: ~19  
  *Middle-aged, high-income customers with very low spending. Likely conservative or selective shoppers.*

- **Cluster 4:**  
  Average Age: ~32  
  Average Annual Income: ~$76,000  
  Average Spending Score: ~78  
  *Young adults with moderately high income and high spending. A financially stable and active consumer segment.*

## Dependencies

- Python 3.x
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## Author

- Nitin Nandan
- Internship Project for CodeClause

---

