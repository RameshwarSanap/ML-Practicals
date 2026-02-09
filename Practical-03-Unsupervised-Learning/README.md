## Aim
To study and implement unsupervised learning algorithms such as K-Means clustering,
Hierarchical clustering, and Principal Component Analysis (PCA) on a given dataset.

---

## Theory

### Unsupervised Learning
Unsupervised learning is a type of machine learning where the model is trained on
unlabeled data. The objective is to identify hidden patterns or structures in the data
without prior knowledge of output labels.

---

### K-Means Clustering
K-Means is a partition-based clustering algorithm that divides the dataset into K clusters.
Each cluster is represented by its centroid, and data points are assigned to the nearest
centroid based on distance.

**Algorithm Steps:**
1. Select the number of clusters (K)
2. Initialize cluster centroids
3. Assign data points to the nearest centroid
4. Update centroids
5. Repeat until convergence

**Squared Error (Inertia):**
It is the sum of squared distances of data points from their respective cluster centroids.
Lower squared error indicates better clustering.

---

### Hierarchical Clustering
Hierarchical clustering builds a tree-like structure (dendrogram) of clusters.
It does not require specifying the number of clusters in advance.

**Types:**
- Agglomerative (bottom-up)
- Divisive (top-down)

Hierarchical clustering is computationally expensive but provides better visualization
of cluster formation.

---

### Comparison: K-Means vs Hierarchical Clustering
- K-Means is faster and efficient for large datasets.
- Hierarchical clustering is slower but gives a clear cluster hierarchy.
- K-Means provides lower squared error in most cases.

---

### Principal Component Analysis (PCA)
PCA is a dimensionality reduction technique used to reduce the number of features
while retaining maximum varianc
