
# Introduction

## Introduction
This lesson summarizes the topics we'll be covering in section 29 and why they'll be important to you as a data scientist.

## Objectives
You will be able to:
* Understand and explain what is covered in this section
* Understand and explain why the section will help you to become a data scientist

## Logistic Regression

You're familiar with linear regression to predict continuous values from module 1. We're now going to return to regression to look at how it can be used as a classifier instead to determine the likelihood of a given data point being associated to one of two categories.

We start by introducing the sigmoid function and showing how it can be used to fit a curve that matches a binary classifier (e.g. does someone make over or under $40k a year or are they a good or bad credit risk).

We then look at the practicalities of evaluating logistic regression models based on our previous experience of using precision, recall and accuracy to evaluate other classifiers.

We also take a little time to look at how to plot a confusion matrix for a logistic regression classifier and introduce a couple of key concepts for determining the optimal precision-recall tradeoff for a given classifier - Receiver Operating Characteristic (ROC) curves and AUC (the Area Under the Curve).

We then introduce the concept of class imbalance problems. Imagine a classifier for cancer where only 1 screened individual in 1000 is sick. You could obtain over 99 percent accuracy by just saying everyone is fine, but that wouldn't be a very useful approach. We look at the ideas of class weights and over/undersampling and how they can be used to work with highly imbalanced classes.


## Summary

It's important to be aware of logistic regression as one potential classifier that you could use, and many of the concepts around model evaluation will be useful whenever you're trying to solve a classification problem.
