#  K-Means + PCA on Iris Dataset

This project applies **K-Means Clustering** and **Principal Component Analysis (PCA)** to the classic Iris dataset.

###  Key Highlights:

- **Data Preprocessing**:
  - Normalized features for consistency.

- **Clustering**:
  - Used K-Means with 3 clusters.
  - Cluster-to-species mapping:
    - Cluster 0 → *Iris-setosa*
    - Cluster 1 → *Iris-virginica*
    - Cluster 2 → *Iris-versicolor*

- **Confusion Matrix**:
  ```
  [[50  0  0]
   [ 0 39 11]
   [ 0 14 36]]
  ```
  - **Clustering Accuracy**: 83.33%

- **PCA Analysis**:
  - Reduced dimensions from 4 to 2 for visualization.
  - Variance Explained:
    - PC1: 72.77%
    - PC2: 23.03%
    - PC3: 3.68%
    - PC4: 0.52%

---
 Built with: NumPy, Pandas, Matplotlib  

