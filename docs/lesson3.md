---
layout: default
title: "Lesson 3: The ML Process"
nav_order: 4
---
# Lesson 3: The Machine Learning Process

## Objectives
- Understand the difference between training data and testing data.
- Learn the importance of keeping training and testing data separate.
- Know the basic steps of the machine learning process.

## Concept(s)

Now that we know about the different categories of machine learning, let's talk about how we actually build a machine learning model. The process is similar to how you would study for a test in school.

Let's say you have a math test coming up. Your teacher gives you a set of practice problems (with the answers) to study from. You use these practice problems to learn the concepts and practice your skills. This is like the **training phase** in machine learning.

Then, on the day of the test, your teacher gives you a new set of problems that you haven't seen before. You use what you learned from the practice problems to solve these new problems. This is like the **testing phase** in machine learning.

### Training Data vs. Test Data
In machine learning, we do something very similar. We take our data and split it into two parts: a **training set** and a **testing set**.

#### Training Set
The training set is the data that we use to **train** our machine learning model. This data is labeled, meaning we know the correct answer for each data point. The model looks at the training data and learns the patterns and relationships between the features and the labels.

The training set is usually the larger of the two sets. A common split is to use 80% of the data for training and 20% for testing.

#### Test Set
The test set is the data that we use to **evaluate** our machine learning model. This data is also labeled, but we don't show the labels to the model. We use the model to make predictions on the test set, and then we compare the model's predictions to the actual labels. This tells us how well our model is performing on new, unseen data.

It's very important that the test set is kept separate from the training set. If the model sees the test data during training, it will simply memorize the answers and it won't learn to generalize to new data. This is like if your teacher gave you the exact same problems on the test that you had on the practice sheet. You might get a good grade on the test, but you wouldn't have actually learned the concepts.

### The Process
Here's a summary of the machine learning process:
1.  **Gather Data:** Collect the data that you will use to train and test your model.
2.  **Split Data:** Split your data into a training set and a testing set.
3.  **Train Model:** Choose a machine learning algorithm and train your model on the training data.
4.  **Evaluate Model:** Use the trained model to make predictions on the test data and evaluate its performance.
5.  **Tune Model:** If you are not happy with the performance of your model, you can go back and tune it. This might involve choosing a different algorithm, or changing some of the settings of the algorithm.
6.  **Use Model:** Once you are happy with the performance of your model, you can use it to make predictions on new, real-world data.

## Practice

Imagine you have a dataset of 100 pictures of cats and dogs, and you want to build a model to classify them.
1. How would you split this data into a training set and a testing set (using an 80/20 split)?
2. Why is it important that your model doesn't see the testing set during training?

...

**Answers:**
1. You would use 80 pictures (80% of 100) for your training set and 20 pictures (20% of 100) for your testing set.
2. If the model sees the testing set during training, it might just memorize the answers for those specific pictures. We want the model to learn the general features of cats and dogs so it can make accurate predictions on pictures it has never seen before.

## Summary
In this lesson, we learned about the machine learning process. We saw that we need to split our data into a **training set** to teach our model and a **testing set** to evaluate its performance. Following a process of gathering data, splitting it, training, evaluating, and tuning helps us build effective models.
