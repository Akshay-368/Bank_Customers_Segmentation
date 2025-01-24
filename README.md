# Bank_Customers_Segmentation
This project aims to segment bank customers based on their account balances and transaction behaviors. By leveraging clustering techniques and dimensionality reduction, we identify patterns in customer data that can be used for targeted marketing, risk analysis, and customer profiling.

*Key Features :*
- Data Preprocessing: Cleaning and handling missing data, imputations, and scaling.
- Dimensionality Reduction: PCA for reducing data to 2 dimensions for clustering visualization.
- Clustering: K-Means clustering with optimal clusters determined using the Elbow method.
- Insights: Interpretations of customer clusters and their business implications.

*Performance Metrics*
Include metrics to assess clustering performance:
- **Silhouette Score:** Measures how well clusters are separated. Higher values indicate better clustering.
- **Inertia:** Measures within-cluster variance. Lower values indicate compact clusters.
- **Explained Variance Ratio (PCA):** Shows how much variance is captured by the principal components.

This project is licensed under the MIT License.


Clone the repository and install the required libraries using pip:
```bash
git clone https://github.com/your-username/bank-customer-segmentation.git
cd bank-customer-segmentation
pip install -r requirements.txt

#### ** Usage**
```markdown
To run the project, use the following scripts:
1. Preprocess the data:
   ```bash
   python scripts/data_preprocessing.py
