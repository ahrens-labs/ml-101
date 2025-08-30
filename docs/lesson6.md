---
layout: default
title: "Lesson 6: Naive Bayes"
nav_order: 7
---
# Lesson 6: Naive Bayes

## Objectives
- Understand the basic idea behind the Naive Bayes algorithm.
- Learn about the "naive" assumption of conditional independence.
- Know the common use cases for Naive Bayes, especially in text classification.

## Concept(s)

Today, we're going to learn about another classification algorithm called **Naive Bayes**. It's a simple but surprisingly powerful algorithm, especially for tasks involving text, like classifying emails as spam or not spam.

### What is Naive Bayes?
Naive Bayes is a classification algorithm based on **Bayes' Theorem**, a famous theorem in probability. The theorem describes the probability of an event, based on prior knowledge of conditions that might be related to the event.

In simpler terms, Naive Bayes calculates the probability of a certain class (e.g., "spam") given a set of features (e.g., the words in an email). It calculates the probability for each class, and then picks the class with the highest probability.

### What's so "Naive" about it?
The "naive" part of the name comes from the main assumption that the algorithm makes: **it assumes that all the features are independent of each other.**

What does this mean? Let's go back to our spam example. The features are the words in the email. The Naive Bayes algorithm assumes that the presence of the word "free" in an email is independent of the presence of the word "money". In reality, these two words are more likely to appear together in a spam email, so they are not truly independent.

This assumption is often not true in the real world, which is why the algorithm is called "naive". However, even with this simplifying assumption, Naive Bayes works very well in practice, especially for text classification.

### When to use Naive Bayes?
Naive Bayes is a great choice for:
- **Text classification:** As we've discussed, it's great for spam filtering, sentiment analysis (determining if a review is positive or negative), and categorizing news articles.
- **Real-time predictions:** It's very fast to train and make predictions, so it's good for situations where you need a quick answer.

## Practice
Time to build a Naive Bayes model. We'll use it to classify text messages as either "spam" or "ham" (not spam).

We've created a Jupyter notebook that will walk you through the process. Click the link below to open it in Google Colab.

[Open Lesson 6 Notebook in Colab](https://colab.research.google.com/github/{{ site.github.repository_nwo }}/blob/main/docs/notebooks/lesson6_naive_bayes.ipynb)

## Summary
In this lesson, we explored the **Naive Bayes** algorithm, a fast and simple classifier based on probability. We learned that its "naive" assumption is that all features are independent, which works surprisingly well for tasks like text classification. We then prepared to build our own spam filter using Naive Bayes in the practice notebook.
