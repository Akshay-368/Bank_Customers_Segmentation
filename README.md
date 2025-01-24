#Bank Customer Segmentation using KMeans and PCA

*Overview*
This project demonstrates clustering bank customers into meaningful segments based on their transaction behavior. The segmentation is performed using Principal Component Analysis (PCA) for dimensionality reduction and KMeans Clustering for grouping customers into clusters.

The dataset was initially a large CSV file, which was converted into a compressed Parquet file format for faster processing and reduced storage requirements.

*Project Workflow*
1).Data Cleaning and Preprocessing:
-Handling missing values.
-Scaling numerical features using StandardScaler.
-Performing dimensionality reduction using PCA.

2). *Clustering:*

-Using the KMeans algorithm to group customers into clusters.
-Determining the optimal number of clusters using the Elbow Method and Davies-Bouldin Index.

3). *Visualization:*

-Visualizing clusters using the reduced dimensions from PCA.
-Interpreting the characteristics of each cluster.

*Compressed Parquet File:*

The dataset was saved as a compressed Parquet (.parquet.gz) file for optimized storage and performance.
Why Parquet Format?
Faster Processing: Parquet files are optimized for query performance and storage efficiency.
Reduced Size: Compression significantly reduces file size, making it suitable for large datasets.
Compatibility: Supported by tools like Pandas, Spark, and other data analysis frameworks.


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
