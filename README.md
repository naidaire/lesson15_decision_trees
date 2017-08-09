# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Logistic-Regression
Unit 4 : Data Modeling | Lesson 3 : Decision Trees & Random Forests

## Materials We Provide

| Topic | Description | Link |
| --- | --- | --- |
| Lesson | Decision Trees | [Here](./decision-trees.ipynb) |
|        | Ensembles & Random Forests | [Here](./ensembles-random-forests.ipynb)
| Solution  | None needed (by-hand group exercises and codealongs) | N/A |
| Datasets | MLB player data | (hitters.csv)[./datasets/hitters.csv]
| Datasets | Titanic survivors | (titanic.csv)[./datasets/titanic.csv]
| Datasets | Vehicles (test) | (vehicles_test.csv)[./datasets/vehicles_test.csv]
| Datasets | Vehicles (train) | (vehicles_train.csv)[./datasets/vehicles_train.csv]
| Source Materials | Original files used to create this lesson | [Here](./assets/slides/) |
| Extra Materials | Examples of Logistic Regression Implementation | [Here](./assets/examples/) |

The MLB player data and Titanic datasets were chosen because they are small enough to make very interpretable decision trees without much tuning. The vehicle data is very small, chosen as an easy example students could do by hand. It also provides a pre-split test set.

---

## Learning Objectives (Decision Trees)
*After this lesson, students will be able to:*

- Explain how a decision tree is created
- Build a decision tree model in scikit-learn
- Tune a decision tree model and explain how tuning impacts the model
- Interpret a tree diagram
- Describe the key differences between regression and classification trees
- Decide whether a decision tree is an appropriate model for a given problem


## Learning Objectives (Ensembles & Decision Trees)

- Understand how and why decision trees can be improved using bagging and random forests
- Build random forest models for classification and regression
- Know how to extract the most important predictors in a random forest model

---

## Lesson Outline (Decision Trees)

- Introduction
- Part 1: Regression trees
    - Group exercise
    - Building a regression tree by hand
    - How does a computer build a regression tree?
    - Demo: Choosing the ideal cutpoint for a given feature
    - Building a regression tree in scikit-learn
    - What happens when we grow a tree too deep?
    - Tuning a regression tree
    - Making predictions for the testing data
- Part 2: Classification trees
    - Comparing regression trees and classification trees
    - Splitting criteria for classification trees
    - Building a classification tree in scikit-learn
- Summary: Comparing decision trees with other models

---

## Lesson Outline (Ensembles & Decision Trees)

- Introduction
- Part 1: Manual Ensembling
- Part 2: Bagging
    - Manually implementing bagged decision trees
    - Bagged decision trees in scikit-learn
    - Estimating out-of-sample error
- Part 3: Random Forests
- Part 4: Building and tuning decision trees and Random Forests
    - OPTIONAL: Predicting salary with a decision tree
    - Predicting salary with a Random Forest
    - Comparing Random Forests with decision trees
- OPTIONAL: Tuning Individual Parameters

---


## Student Requirements
Before this lesson(s), students should already be able to:

- Know how to build and evaluate (classification) models in sklearn
- Knowledge of resampling methods
- Understand the concepts of cross-validation and overfitting


----

## Additional Resources

*If you're interested in reading more about decision trees and random forests, check these out:*
- [Induction of Decision Trees](http://hunch.net/~coms-4771/quinlan.pdf)
- [Top 10 Algorithms in Data Mining](http://www.cs.uvm.edu/~icdm/algorithms/10Algorithms-08.pdf)


*Also, I highly recommend checking out the following books:*
- __CHAPTER 8__ - [An Introduction to Statistical Learning](http://www-bcf.usc.edu/~gareth/ISL/) - This book provides a fantastic introduction to machine learning models and the statistics behind them. The visuals and explanations are really easy to understand. PDF available to download on the website.
- __CHAPTER 9__ - [Elements of Statistical Learning](http://statweb.stanford.edu/~tibs/ElemStatLearn/) - This book is by most of the same authors as the previous book, but goes into more detail. PDF available to download on the website.
- __CHAPTER 8__ - [Applied Predictive Modeling](https://www.amazon.com/Applied-Predictive-Modeling-Max-Kuhn/dp/1461468485) - While this book features R code, the discussion of different predictive models and sampling methodologies are hard to beat.  



<img src="https://images-na.ssl-images-amazon.com/images/I/41oQwj8rS0L._SX329_BO1,204,203,200_.jpg" width="180">
<img src="https://images-na.ssl-images-amazon.com/images/I/41aQrQaPseL._SX331_BO1,204,203,200_.jpg" width="180">
<img src="https://images-na.ssl-images-amazon.com/images/I/41S7RyAnsLL._SX313_BO1,204,203,200_.jpg" width="180">
