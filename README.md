# Zeotap_Data_Science_Intern
Here’s the updated **README file** with direct raw links for accessing the files:

---

# eCommerce Transactions Dataset Analysis

## Overview
This repository contains the solution to the **eCommerce Transactions Dataset** analysis. The dataset consists of customer, product, and transaction data. The task involves performing **Exploratory Data Analysis (EDA)**, building a **Lookalike Model**, and applying **Customer Segmentation** using clustering techniques to generate actionable business insights.

The solution includes Jupyter Notebooks for all tasks, CSV files for lookalike recommendations, and business insights based on the dataset.


## Task 1: Exploratory Data Analysis (EDA) and Business Insights

### Steps:
1. Clean and merge the provided dataset.
2. Perform exploratory data analysis to understand patterns in customer behavior, products, and transactions.
3. Derive at least 5 business insights based on the analysis.

### Deliverables:
- **EDA Notebook**: `Likhith_Raj_EDA.ipynb`
- **Business Insights PDF**: `Likhith_Raj_EDA.pdf`

### Insights (Example):
1. **Most Active Region**: South America had the highest number of orders, with a total of 59 orders.
2. **Top-Selling Category**: Books emerged as the most sold product category in 2024.
3. **Top Customer**: Customer C0109 was the most active, having placed 11 orders.
4. **Peak Transaction Month**: January 2024 recorded the highest number of transactions.
5. **Revenue Trends**: Total revenue in 2024 reached $332,669.30, with significant contributions from South Africa.

---

## Task 2: Lookalike Model

### Steps:
1. Build a model that takes customer information and recommends the 3 most similar customers based on transaction and profile data.
2. Calculate similarity using cosine similarity.
3. Output a CSV file (`Lookalike.csv`) containing recommended lookalikes for each customer.

### Deliverables:
- **Lookalike CSV**: `Lookalike.csv`
- **Lookalike Model Notebook**: `Likhith_Raj_Lookalike.ipynb`

### Example (for Customer C0003):
- **Lookalike 1**: C0190, Similarity Score: 0.9546
- **Lookalike 2**: C0091, Similarity Score: 0.9086
- **Lookalike 3**: C0174, Similarity Score: 0.9045

---

## Task 3: Customer Segmentation / Clustering

### Steps:
1. Perform customer segmentation using clustering techniques.
2. Use customer profile and transaction data for clustering.
3. Choose a suitable clustering algorithm (e.g., KMeans) and evaluate the clustering using the Davies-Bouldin Index (DBI).
4. Visualize the clusters and analyze the results.

### Deliverables:
- **Clustering Report PDF**: `Likhith_Raj_Clustering.pdf`
- **Clustering Notebook**: `Likhith_Raj_Clustering.ipynb`

### Clustering Evaluation:
- **3 Clusters**: DBI = 0.89
- **4 Clusters**: DBI = 1.03
- **9 Clusters**: DBI = 0.721 (Best configuration)

---

## Google Colab Links
- [Task 1: EDA and Business Insights](https://colab.research.google.com/drive/1apsczs9x__YEUl8L6PcF6iFvw1jAyKn7?usp=drive_link)
- [Task 2: Lookalike Model](https://colab.research.google.com/drive/1MHs2rP_Hkcs3IMrURgBBFk2PzUo_BKw?usp=drive_link)
- [Task 3: Customer Segmentation / Clustering](https://colab.research.google.com/drive/1PaX0MM4w8EstBIxatRJen_5LuBkzkmsV?usp=drive_link)

---

## How to Run the Code:
1. Clone this repository or download the notebook files.
2. Open the notebooks in Jupyter or Google Colab.
3. Ensure you have the required libraries installed:
   - `pandas`
   - `numpy`
   - `scikit-learn`
   - `matplotlib`
   - `seaborn`
4. Run each cell in the notebook to execute the tasks.
