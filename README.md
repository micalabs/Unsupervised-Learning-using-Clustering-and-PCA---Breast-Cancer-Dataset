# Unsupervised-Learning-using-Clustering-and-PCA---Breast-Cancer-Dataset

# Unsupervised Learning - Using Clustering Techniques and Principal Component Analysis (PCA) Method

Some of the most important unsupervised machine learning techniques are Clustering (K-Means and Hierarctical Clustering) and Principal Component Analysis (PCA). 

This tutorial shows how to implement Principal Component Analysis and Clustering in Python

In Unsupervised learning, the data is not being labelled. it looks for previously undetected patterns without human intervention or supervision. In case of unsupervised learning the data points are grouped as belonging to a cluster based on similarity. Similarity can be measured by plotting a data-point in n-dimensional vector space and finding euclidean distance between data-points. The less the distance, the more similar they are.

The Dataset (Breast Cancer Dataset) for this Tutorial can be Downloaded from this link - https://www.mldata.io/dataset-details/breast_cancer/

# Challenges in Unsupervised learning
- Unsupervised learning is harder in comparison to Supervised learning as there is no annotated data, so the algorithms need to be such that it understands the pattern.
- Unsupervised learning results cannot be validated since no labelled data is present.
# Advantages of Unsupervised learning
- There is no manual labeling required for annotating huge amount of data
- We don’t know how many classes the data is actually divided.
- Principal Component Analysis reduces the dimension of large data-set, thus helping in less computation.
# Principal Component Analysis(PCA)
Large data-sets are widespread in many sectors. In order to analyse and interpret such data-sets, methods are required to significantly reduce the dimensionality in an interpretable way, such that most of the information is preserved. Many techniques have been developed, but principal component analysis (PCA) is one of the oldest and widely used. Its idea is simple, reduce the dimensionality of a dataset, on the other hand, preserving as much ‘variability’ (i.e. statistical information) as possible.

The cell nuclei categories in the dataset will be used to predict whether a breast cancer tumor is "benign" or "malignant"
