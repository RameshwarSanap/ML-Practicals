## 📘 Practical No. 03 – Unsupervised Learning

### 🎯 Aim

To study and implement unsupervised learning techniques such as K-Means Clustering, Hierarchical Clustering, and Principal Component Analysis (PCA) on a given dataset and analyze their performance.

---

## 🔹 Unsupervised Learning

Unsupervised learning is a type of machine learning in which the model is trained using unlabeled data. The main objective is to discover hidden patterns, structures, or groupings in the data without prior knowledge of output labels.

---

## 🔹 K-Means Clustering

K-Means is a partition-based clustering algorithm that divides the dataset into **K clusters**. Each cluster is represented by its centroid, and data points are assigned to the nearest centroid based on distance.

### 🔸 Steps:

1. Select number of clusters (K)
2. Initialize centroids randomly
3. Assign data points to nearest centroid
4. Update centroids
5. Repeat until convergence

### 🔸 Squared Error (Within Cluster Sum of Squares – WCSS)

Squared error measures the compactness of clusters.
Lower WCSS indicates better clustering.

---

## 🔹 Optimal Number of Clusters (Elbow Method)

The elbow method is used to determine the optimal value of K by plotting WCSS against different K values. The point where the decrease in WCSS slows down forms an “elbow”, which indicates the optimal number of clusters.

---

## 🔹 Hierarchical Clustering

Hierarchical clustering builds a hierarchy of clusters either using:

* **Agglomerative (bottom-up)** approach
* **Divisive (top-down)** approach

Clusters are formed based on distance metrics and linkage criteria such as single, complete, or average linkage.

### 🔸 Squared Error in Hierarchical Clustering

For different numbers of clusters, squared error is computed and stored to compare clustering performance.

---

## 🔹 Comparison: K-Means vs Hierarchical Clustering

| Parameter          | K-Means             | Hierarchical           |
| ------------------ | ------------------- | ---------------------- |
| Cluster Type       | Partition-based     | Tree-based             |
| Need of K          | Required            | Not required initially |
| Speed              | Fast                | Slower                 |
| Scalability        | Good for large data | Better for small data  |
| Error Optimization | Direct              | Indirect               |

---

## 🔹 Principal Component Analysis (PCA)

PCA is a dimensionality reduction technique that transforms high-dimensional data into a lower-dimensional space while preserving maximum variance.

### 🔸 Objectives:

* Reduce dimensionality
* Remove redundant features
* Improve visualization and performance

---

## 🔹 Variance Explained

Each principal component explains a certain percentage of total variance. Components with higher variance are more significant.

---

## 🔹 Visualization

The transformed data is visualized using 2D or 3D scatter plots to understand data distribution after dimensionality reduction.

---

## 🧰 Tools & Libraries Used

* Python
* Google Colab
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

---

## ✅ Conclusion

In this practical, K-Means and Hierarchical clustering were implemented and compared using squared error. PCA was applied for dimensionality reduction and visualization, demonstrating the effectiveness of unsupervised learning techniques.
