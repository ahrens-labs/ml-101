---
layout: default
title: "Lesson 7: K-Nearest Neighbors"
nav_order: 8
---
# Lesson 7: K-Nearest Neighbors

## Objectives
- Understand the intuition behind the K-Nearest Neighbors (KNN) algorithm.
- Learn how KNN makes predictions for classification tasks.
- Understand the role of 'K' and how it affects the model.

## Concept(s)

Today we'll learn about a very intuitive algorithm called **K-Nearest Neighbors (KNN)**. It's a type of "lazy learning" algorithm, which means it doesn't learn a "model" in the same way that other algorithms do. Instead, it just memorizes the entire training dataset.

### How does KNN work?
The main idea behind KNN is that you can predict the class of a new data point by looking at the classes of its closest neighbors.

Imagine you're in a new school and you don't know anyone. You want to guess if a new student, Alex, plays sports. You could look at the 5 students who sit closest to Alex. If 4 of them are on the soccer team, you might guess that Alex also plays sports. That's the basic idea of KNN!

Here's how it works in a more formal way:
1.  **Choose a value for K:** K is the number of neighbors to look at. This is a number you choose.
2.  **Find the K nearest neighbors:** For a new data point, find the K data points in the training set that are closest to it. "Closeness" is usually measured using Euclidean distance (the straight-line distance between two points).
3.  **Make a prediction:** For classification, you take a "vote" among the K neighbors. The new data point is assigned to the class that is most common among its K neighbors.

### Choosing the right K
The value of K is very important.
- If **K is too small**, the model can be very sensitive to noise and outliers. A single mislabeled data point could change the prediction.
- If **K is too large**, the model might become too "generalized" and miss the local patterns in the data.

Choosing the right value for K is a process of experimentation. You often try a few different values for K and see which one works best for your data.

## Practice
Let's see KNN in action. We'll use it to classify different types of flowers based on their petal and sepal measurements.

We've created a Jupyter notebook that will guide you through building a KNN model. Click the link below to open it in Google Colab.

[Open Lesson 7 Notebook in Colab](https://colab.research.google.com/github/{{ site.github.repository_nwo }}/blob/main/docs/notebooks/lesson7_knn.ipynb)

## Summary
In this lesson, we learned about the **K-Nearest Neighbors (KNN)** algorithm, a simple and intuitive classifier. It works by assigning a new data point to the class that is most common among its 'K' closest neighbors in the training data. We also learned that choosing the right value for 'K' is a critical step in building an effective KNN model.
