# Zeotap_Data_Science_Intern
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
