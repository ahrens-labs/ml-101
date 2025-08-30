---
layout: default
title: "Lesson 8: K-Means Clustering"
nav_order: 9
---
# Lesson 8: K-Means Clustering

## Objectives
- Understand what clustering is and how it's different from classification.
- Learn the basic steps of the K-Means clustering algorithm.
- Know how to interpret the output of a K-Means model.

## Concept(s)

Welcome to our final modeling lesson! So far, we've focused on supervised learning (classification and regression). Today, we're going to dive into the world of **unsupervised learning** with an algorithm called **K-Means Clustering**.

### What is Clustering?
Remember in Lesson 2, we talked about unsupervised learning? This is where we have unlabeled data and we want to find patterns in it. Clustering is the most common type of unsupervised learning.

The goal of clustering is to group similar data points together into clusters. The data points in a cluster should be similar to each other, and different from the data points in other clusters.

### How does K-Means work?
K-Means is one of the most popular clustering algorithms. The 'K' in K-Means represents the number of clusters you want to find. You have to choose this value upfront.

Here's a simplified view of how the K-Means algorithm works:
1.  **Choose K:** Decide how many clusters you want to find.
2.  **Initialize Centroids:** Randomly place K points on your data plot. These points are called "centroids" and they will be the initial centers of your clusters.
3.  **Assign Data Points to Clusters:** Assign each data point to the closest centroid. This creates K clusters.
4.  **Update Centroids:** Recalculate the center of each cluster by finding the average of all the data points in that cluster. This new center becomes the new centroid.
5.  **Repeat:** Repeat steps 3 and 4 until the centroids stop moving much.

When the algorithm is finished, you'll have K clusters, each with its own centroid at the center.

### When to use K-Means?
K-Means is great for:
- **Customer segmentation:** Grouping customers with similar behaviors.
- **Document analysis:** Grouping similar documents together.
- **Image compression:** Grouping similar colors together.

## Practice
Let's use K-Means to find clusters in a dataset of customer information. We'll try to group customers based on their age and spending score.

We've created a Jupyter notebook that will guide you through this process. Click the link below to open it in Google Colab.

[Open Lesson 8 Notebook in Colab](https://colab.research.google.com/github/{{ site.github.repository_nwo }}/blob/main/docs/notebooks/lesson8_kmeans.ipynb)

## Summary
In this lesson, we learned about **K-Means Clustering**, a popular unsupervised learning algorithm. It groups unlabeled data into a pre-selected number (K) of clusters by iteratively finding the best centers (centroids) for those clusters. This is useful for discovering natural groupings in data, like customer segments.
