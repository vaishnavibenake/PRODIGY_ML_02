# PRODIGY_ML_02

## Customer Segmentation using K-Means Clustering

### Task Objective

Create a K-Means clustering algorithm to group customers of a retail store based on their purchase-related behavior.

### Dataset

The project uses the **Mall Customers** dataset from Kaggle:

[Customer Segmentation Tutorial in Python](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)

The dataset contains information about 200 customers, including:

- Customer ID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

### Features Used

For customer segmentation, the following two features were selected:

- **Annual Income (k$)**
- **Spending Score (1-100)**

These features were used because they provide information about customers' income and spending behavior.

### Methodology

The following steps were performed:

1. Loaded and explored the customer dataset.
2. Checked for missing values.
3. Selected Annual Income and Spending Score as clustering features.
4. Visualized the customer data before clustering.
5. Used the **Elbow Method** to determine a suitable number of clusters.
6. Selected **K = 5** based on the Elbow Method.
7. Applied the K-Means clustering algorithm.
8. Assigned each customer to a cluster.
9. Calculated the average income and spending score for each cluster.
10. Interpreted the characteristics of the resulting customer segments.

### Customer Segments

The five clusters showed different income and spending patterns:

| Cluster | Customer Segment |
|---|---|
| Cluster 0 | Medium income and medium spending |
| Cluster 1 | High income and high spending |
| Cluster 2 | Low income and high spending |
| Cluster 3 | High income and low spending |
| Cluster 4 | Low income and low spending |

### Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab
- Jupyter Notebook

### Key Learning

This task provided practical experience with **unsupervised machine learning** and **K-Means clustering**. It demonstrated how customer data can be grouped into meaningful segments based on similarities in their income and spending behavior.

### Files

- `customer_segmentation_kmeans.ipynb` — Jupyter Notebook containing the complete implementation and analysis.

### Internship

**Machine Learning Internship — Prodigy InfoTech**

Task: **PRODIGY_ML_02**
