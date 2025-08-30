---
layout: default
title: "Lesson 5: Logistic Regression"
nav_order: 6
---
# Lesson 5: Logistic Regression

## Objectives
- Understand what logistic regression is and that it's used for classification.
- Learn how logistic regression differs from linear regression.
- Know what a sigmoid function is and how it's used to calculate probability.

## Concept(s)

In the last lesson, we learned about linear regression, which is used to predict a continuous value. In this lesson, we're going to learn about **Logistic Regression**, which is used for **classification** problems.

### What is Logistic Regression?
Don't be fooled by the name! Even though it has "regression" in its name, logistic regression is a **classification** algorithm. This means it's used to predict a category, not a number.

Remember in Lesson 2 when we talked about classification? We said that classification is when we want to predict a label that can only be one of a few different things. Logistic regression is perfect for this.

So, when would you use logistic regression? Here are a few examples:
- To predict if an email is spam or not spam.
- To predict if a student will pass or fail a test.
- To predict if a customer will buy a product or not.

In all of these cases, there are only two possible outcomes. This is called **binary classification**. Logistic regression is great for binary classification problems.

### How is it different from Linear Regression?
Linear regression fits a straight line to the data. Logistic regression is a bit different. It uses a special function called the **sigmoid function** to squeeze the output between 0 and 1.

The output of the sigmoid function can be interpreted as a **probability**. For example, if we're trying to predict if an email is spam, a logistic regression model might output 0.9. This means that the model is 90% confident that the email is spam.

We can then set a threshold (usually 0.5) to make a final decision. If the probability is greater than 0.5, we classify it as "spam". If it's less than 0.5, we classify it as "not spam".

## Practice
Now it's time to build our own logistic regression model. We've created a Jupyter notebook that will walk you through the process of building a simple logistic regression model in Python.

We'll be using a dataset of students' exam scores. We'll build a model that can predict whether a student will pass or fail based on their scores on two exams.

Click the link below to open the notebook in Google Colab.

[Open Lesson 5 Notebook in Colab](https://colab.research.google.com/github/{{ site.github.repository_nwo }}/blob/main/docs/notebooks/lesson5_logistic_regression.ipynb)

## Summary
In this lesson, we learned about **Logistic Regression**, a classification algorithm used to predict one of two outcomes. Unlike linear regression, it uses a **sigmoid function** to output a probability between 0 and 1. We then prepared to use this for a practical problem: predicting whether a student will pass or fail in our hands-on notebook.
