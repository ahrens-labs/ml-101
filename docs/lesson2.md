---
layout: default
title: "Lesson 2: Categories of ML"
nav_order: 3
---
# Lesson 2: Categories of Machine Learning

## Objectives
- Learn about the main categories of machine learning: Supervised and Unsupervised Learning.
- Understand the difference between Classification and Regression.
- Know what Clustering is used for.

## Concept(s)

In the last lesson, we learned some of the basic vocabulary of machine learning. Now, let's talk about the different types of problems that machine learning can solve. There are three main categories of machine learning: **Supervised Learning**, **Unsupervised Learning**, and **Reinforcement Learning**. In this course, we'll be focusing on the two most common categories: Supervised and Unsupervised Learning.

**Classification** and **Regression** fall under Supervised Learning, while **Clustering** is a type of Unsupervised Learning.

### Supervised Learning
Supervised learning is when we have **labeled data**. This means that we know the "right answer" for each piece of data. We use this labeled data to train our model. The goal of supervised learning is to create a model that can predict the label for new, unseen data.

There are two main types of supervised learning problems: **classification** and **regression**.

#### Classification
Classification is when we want to predict a **category**. The label is a discrete value, meaning it can only be one of a few different things.

Here are some examples of classification problems:
- Is this email spam or not spam? (The categories are "spam" and "not spam")
- Is this a picture of a cat or a dog? (The categories are "cat" and "dog")
- What is the weather going to be like tomorrow? (The categories could be "sunny", "cloudy", "rainy", or "snowy")

In these examples, we are trying to classify the data into one of a few different categories.

#### Regression
Regression is when we want to predict a **continuous value**. This means that the label can be any number within a range.

Here are some examples of regression problems:
- How much will this house sell for? (The price could be any number)
- What will the temperature be tomorrow? (The temperature could be any number)
- How many points will this basketball player score in their next game? (The number of points could be any number)

In these examples, we are trying to predict a specific number, not a category.

### Unsupervised Learning
Unsupervised learning is when we have **unlabeled data**. This means that we don't know the "right answer" for each piece of data. The goal of unsupervised learning is to find patterns and structure in the data on its own.

#### Clustering
Clustering is a type of unsupervised learning where we try to group similar data points together. The goal is to create clusters of data where the data points in each cluster are similar to each other, and different from the data points in other clusters.

Here are some examples of clustering problems:
- Grouping customers into different segments based on their purchasing behavior.
- Grouping similar news articles together.
- Grouping similar songs together to create a playlist.

In these examples, we are not trying to predict a label. We are trying to find the natural groupings in the data.

## Practice

For each of the following scenarios, decide if it is a **Classification**, **Regression**, or **Clustering** problem.

1.  Predicting if a stock price will go up or down.
2.  Grouping photos of animals into different species.
3.  Predicting the exact height of a tree.
4.  Sorting movies into genres like "comedy", "drama", and "action".

...

**Answers:**
1.  **Classification** (the categories are "up" and "down").
2.  **Clustering** (grouping similar items without pre-defined labels).
3.  **Regression** (predicting a continuous value).
4.  **Classification** (the categories are the genres).

## Summary
In this lesson, we explored the main categories of machine learning. We learned that **Supervised Learning** uses labeled data for tasks like **Classification** (predicting categories) and **Regression** (predicting numbers). We also learned that **Unsupervised Learning** finds patterns in unlabeled data, with **Clustering** being a key example where similar data points are grouped together.
