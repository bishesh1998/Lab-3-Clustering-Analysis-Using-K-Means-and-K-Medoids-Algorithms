Lab 3: Clustering Analysis Using K-Means and K-Medoids Algorithms

Name: Bishesh
Institution Affiliation

GitHub: Lab 3 Repository

Purpose

This lab applies clustering techniques to the Wine dataset from sklearn using K-Means and K-Medoids algorithms. The goal is to analyze cluster formation, compare clustering performance, and evaluate results using Silhouette Score and Adjusted Rand Index (ARI).

Key Insights

K-Means: Silhouette Score = 0.2849, ARI = 0.8975

K-Medoids: Silhouette Score = 0.2676, ARI = 0.7411

K-Means produced clusters more closely aligned with true wine classes.

Scatterplots confirmed both algorithms captured similar groupings, but K-Means better recovered the underlying structure.

K-Medoids is robust to outliers but showed lower alignment in this dataset.

Challenges / Decisions

Standardization of features was necessary to improve clustering performance.

Choice of k = 3 was based on the known number of wine classes.

K-Medoids required careful selection of medoids to ensure meaningful clustering.
