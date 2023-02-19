# Sampling
Sampling is a process of selecting a portion or subset (sample) of the population to represent the entire population.

## Description
We are given a dataset on credit cards. The dataset is imbalanced. So, it is balanced by using random over sampling technique. After balancing the dataset, different sampling techniques are used, and 5 different models have been applied to get the accuracy on testing dataset. The dataset is divided into testing and training set.

## Methodology used
1. Balancing the Dataset
2. Creating different types of samples using various sampling techniques
3. Training different ML models
4. Testing the models
5. Analysis of the obtained results

## Sampling Technique Description and Sampling Size Formula

1. Simple Random Sampling
A simple random sample is a subset of a statistical population in which each member of the subset has an equal probability of being chosen.

2. Stratified Sampling
Stratified sampling is a method of sampling that involves the division of a population into smaller subgroups known as strata.

3. Systematic Sampling
Systematic sampling is a probability sampling method where we select members of the population at a regular interval.
Samples taken on every 5th interval

4. Cluster Sampling
Cluster sampling is a probability sampling method in which we divide a population into clusters and then randomly select some of these clusters as sample.

5. Multi-Stage Sampling
In this method we have used a combination of sampling technique, i.e. cluster and simple random. The dataset is divided into clusters and then random samples are chosen from those clusters.


## Resultant Table
|                        | Simple Random | Stratified | Systematic | Cluster | Multi-Satge |
| ---------------------- | ------------- | ---------- | ---------- | ------- | ----------- |
| Logistic Regression    |91.01          |91.32       |79.22       |88.46    |96.00        |
| Decision Tree          |98.50          |96.93       |90.90       |98.46    |96.00        |
| Support Vector Machine |69.66          |63.26       |70.12       |71.53    |56.00        |
| Gaussian Naive Bayes   |76.02          |75.00       |77.92       |63.07    |48.00        |
| K-Nearest Neighbors    |98.12          |95.91       |92.20       |93.07    |82.00        |

## Discussion
From the above table, we can conclude that maximum accuracy is achieved when we apply Decision Tree Algorithm upon taking samples using the Simple Random Sampling technique. We get an accuracy of 98.50%.


## Submission by
Name : Aarushi Abrol
Roll No. : 102003527
Sub-Group: 3CO3
