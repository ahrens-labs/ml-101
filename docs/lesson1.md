---
layout: default
title: "Lesson 1: Definitions"
nav_order: 2
---
# Lesson 1: Definitions

## Objectives
- Understand the basic vocabulary of machine learning.
- Learn what data, features, and labels are.
- Differentiate between an algorithm and a model.

## Concept(s)

Before we can dive into building machine learning models, we need to learn some basic vocabulary. These are the building blocks of machine learning.

### Data
Data is the foundation of machine learning. It's the information that we feed into our machine learning models. Data can be anything from a collection of pictures, to a list of numbers, to a bunch of text.

For example, if we want to build a model that can tell the difference between cats and dogs, our data would be a collection of pictures of cats and dogs.

### Features
Features are the individual properties or characteristics of our data. They are the things that our machine learning model will use to make predictions.

In our cat and dog example, the features could be things like:
- The color of the animal's fur
- The shape of its ears
- The length of its tail
- Its weight

We can represent our features as a set of numbers. For example, we could represent the color of the fur with a number (e.g., 1 for brown, 2 for black, 3 for white).

### Labels
A label is the answer that we want our machine learning model to predict. It's what we are trying to figure out.

In our cat and dog example, the label would be whether the picture is of a "cat" or a "dog". We would go through our data and label each picture with the correct answer. This is called "labeled data".

So, for each picture (our data), we would have a set of features (fur color, ear shape, etc.) and a label ("cat" or "dog").

### Algorithm vs. Model
These two terms are often used interchangeably, but they mean different things.

- **Algorithm:** An algorithm is a set of rules or instructions that a machine learning model follows to learn from data. It's like a recipe. There are many different machine learning algorithms, each with its own strengths and weaknesses. In this course, we'll learn about several different algorithms.

- **Model:** A model is what is created after you have trained an algorithm on your data. It's the output of the machine learning algorithm. The model is what you will use to make predictions on new, unseen data. So, you use an algorithm to *train* a model. The model is the "thing" that does the predicting.

Think of it this way: the algorithm is the process of learning, and the model is the knowledge that is learned.

## Practice
Let's think about another example. Imagine you want to build a model to predict the price of a pizza.

- What is the **data** in this case?
- What are some **features** you could use?
- What is the **label**?

Think about it for a minute before looking at the answers below.

...

**Answers:**
- **Data:** A collection of information about different pizzas.
- **Features:** Size of the pizza, number of toppings, type of crust, etc.
- **Label:** The price of the pizza.

## Summary
In this lesson, we learned the basic terms used in machine learning. We learned that **data** is the information we use, **features** are the characteristics of that data, and **labels** are what we want to predict. We also learned that an **algorithm** is used to train a **model**, which is then used to make predictions.
