# DS 5230 - Unsupervised Machine Learning - Final Project

Customer Segmentation using Clustering & Dimensionality Reduction on Online Retail Dataset

Project by: Pratik Dahibhate and Rivana Christie

Link to dataset: https://archive.ics.uci.edu/ml/datasets/Online+Retail+II

As part of this project, we are using dimensionality reduction and clustering to segment the users from an online retail dataset. We use principal component analysis (PCA) for dimensionality reduction. Then we apply the following clustering techniques on the reduced dataset:

1. K-Means Clustering
2. K-Mean Mini Batch Clustering
3. Gaussian Mixture Model

Furthermore, we perform RFM segmentation on the dataset to segment the users based on their spending habits using the following clustering algorithms:

1. K-Means Clustering
2. Spectral Clustering
3. Gaussian Mixture Model

RFM Segmentation
RFM segmentation is mainly used for marketing products or content to users based on their habits of interaction with the system. Marketers can basically use this method to maximize impressions on their website such as high click-rate, frequent online orders, etc. 
RFM stands for recency, frequency and monetary, each of which are traits exhibited by the users that interact with a particular website. In this section, we will derive the recency, frequency and monetary features based on the columns from the dataset. And then, we will use this transformed dataset to segment the users based on their spending habits.

From our analysis, we conclude that the clusters formed by using RFM segmentation were much more defined and easily interpretable. These clusters can inform further analysis that we do and can also help in providing personalized recommendations to users based on their previous orders and how frequently they order.
