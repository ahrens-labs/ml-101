---
layout: default
title: "Lesson 4: Linear Regression"
nav_order: 5
---
# Lesson 4: Linear Regression

## Objectives
- Understand what linear regression is and when to use it.
- Learn the basic mathematical concept behind a linear model.
- Know how to interpret the output of a simple linear regression model.

## Concept(s)

Welcome to our first modeling lesson! We're going to start with one of the simplest and most common types of regression models: **Linear Regression**.

### What is Linear Regression?
Remember in Lesson 2 when we talked about regression? We said that regression is when we want to predict a continuous value. Linear regression is a way to do that by fitting a straight line to our data.

Imagine you have a scatter plot of data points. Linear regression tries to find the straight line that best fits through the data points. The line is a "model" of the relationship between the variables. Once we have the line, we can use it to predict the value of one variable based on the value of the other.

Let's look at an example. Let's say we have data about the height and weight of a group of people. We can plot this data on a scatter plot, with height on the x-axis and weight on the y-axis. We would probably see that as height increases, weight also tends to increase.

Linear regression would help us find the straight line that best represents this relationship. We can then use this line to predict the weight of a person given their height.

### The Math Behind It (Just a little bit!)
The equation for a straight line is:
`y = mx + b`

- `y` is the value we are trying to predict (in our example, weight). This is our **label**.
- `x` is the value we are using to make the prediction (in our example, height). This is our **feature**.
- `m` is the **slope** of the line. It tells us how much `y` changes for every one unit increase in `x`.
- `b` is the **y-intercept**. It's the value of `y` when `x` is 0.

The goal of linear regression is to find the values of `m` and `b` that create the line that best fits the data.

## Practice
Now it's time to get our hands dirty and build our own linear regression model. We've created a Jupyter notebook that will walk you through the process of building a simple linear regression model in Python.

We'll be using a dataset of house prices. We'll build a model that can predict the price of a house based on its size.

Click the link below to open the notebook in Google Colab. You'll need to be logged into a Google account.

[Open Lesson 4 Notebook in Colab](https://colab.research.google.com/github/{{ site.github.repository_nwo }}/blob/main/docs/notebooks/lesson4_linear_regression.ipynb)

## Summary
In this lesson, we learned about **Linear Regression**, a model used to predict continuous values by fitting a straight line to data. We saw that this line is represented by the equation `y = mx + b`, where the goal is to find the best `m` (slope) and `b` (intercept). We then prepared to apply this concept by building a model to predict house prices in our practice notebook.
