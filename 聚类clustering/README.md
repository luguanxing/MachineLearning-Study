# 聚类算法 Clustering

聚类算法是一类用于将数据集划分为多个组（簇）的无监督学习算法。每个组中的数据点在某种意义上应该是相似的，而不同组之间的数据点应该是不同的。以下是一些常见的聚类算法：

Clustering algorithms are a type of unsupervised learning algorithms used to divide a dataset into multiple groups (clusters). The data points within each group should be similar in some sense, while data points in different groups should be distinct. Here are some common clustering algorithms:

<br/>

每种聚类算法都有其适用的场景和优缺点：
 - K-Means 适用于速度要求高，簇形状相似的数据。
 - 层次聚类 适合探索数据的层次结构，但不适合大数据。
 - DBSCAN 适合处理含有噪声和异常值的数据，且不用预设簇数。
 - Mean Shift 和 谱聚类 适合处理复杂形状的簇，但计算代价较高。
 - GMM 适合软聚类和不同方差的簇。
 - Affinity Propagation 和 Birch 适合自动确定簇数和处理大规模数据。

   
Each clustering algorithm has its applicable scenarios, along with its advantages and disadvantages:
 - K-Means is suitable for high-speed requirements and datasets with clusters of similar shape.
 - Hierarchical Clustering is good for exploring the hierarchical structure of data but is not suitable for large datasets.
 - DBSCAN is ideal for handling data with noise and outliers and does not require a predefined number of clusters.
 - Mean Shift and Spectral Clustering are suitable for dealing with clusters of complex shapes, though they come with higher computational costs.
 - GMM (Gaussian Mixture Model) is effective for soft clustering and clusters with different variances.
 - Affinity Propagation and Birch are well-suited for automatically determining the number of clusters and handling large-scale data.

<br/>

<img width="704" alt="image" src="https://github.com/user-attachments/assets/127f957b-638a-43ec-a374-2c39bed29737">
