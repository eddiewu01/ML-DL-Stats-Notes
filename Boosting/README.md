# Boosting
This note outlines boosting and a few common variations of it.

## What is boosting?
Generally, it is an ensemble method that improves the model predictions of any given learner (typically converts weak learners to strong learners), through process of learning from past errors/mistakes. Let's take a look at a few variations (algorithms) of it to get a better, more specific understanding.

## AdaBoost
It is usually used with decision trees but the those trees are usually just a node and 2 leaves, which are called stumps.

In random forest, each tree's vote has the same weights. But in adaboost, each stump can have a different weight. So the order of stumps are important, because each stump takes the previous mistake into account.

Consider the following example 

| chest pain | block artery | weight | heart disease | Some weight | 
|:----------:|:------------:|:------:|:-------------:|:-----------:|
| Y          | Y            | 205    | Y             | 1/4         |
| N          | Y            | 180    | Y             | 1/4         |
| Y          | N            | 210    | Y             | 1/4         |
| Y          | Y            | 167    | Y             | 1/4         |

1. Assign some weight to indicate how important it is to be correctly classified. At the start all samples get the same weight 1/(total number of samples)
2. 

