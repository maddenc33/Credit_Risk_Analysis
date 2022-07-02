# Credit_Risk_Analysis

## Module 17 Challenge

#### by Christopher Madden

## Overview

Machine learning is the use of statistical algorithms to perform tasks such as learning from data patterns and making predictions. There are many different models—a model is a mathematical representation of something that happens in the real world. Broadly speaking, machine learning can be divided into three learning categories: supervised, unsupervised, and deep. In this module we will explore supervised machine learning. Supervised learning deals with labeled data. An example of supervised learning might be to predict, based on data from previous patients, whether a new patient has diabetes.

To complete the challenge, the following skills are required:
- Explain how a machine learning algorithm is used in data analytics.
- Create training and test groups from a given data set.
- Implement the logistic regression, decision tree, random forest, and support vector machine algorithms.
- Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms.
- Compare the advantages and disadvantages of each supervised learning algorithm.
- Determine which supervised learning algorithm is best used for a given data set or scenario.
- Use ensemble and resampling techniques to improve model performance.


## Results

**Random Oversampler**
![Img1](https://github.com/maddenc33/Credit_Risk_Analysis/blob/main/Images/Img1.png?raw=true)

- Balanced Accuracy Score: 0.6249984891886339
- Precision: 0.99
- Recall Score: 0.65

---
**SMOTE**
![Img2](https://github.com/maddenc33/Credit_Risk_Analysis/blob/main/Images/Img2.png?raw=true)

- Balanced Accuracy Score: 0.6512584051472337
- Precision: 0.99
- Recall Score: 0.66

---
**ClusterCentroids**
![Img3](https://github.com/maddenc33/Credit_Risk_Analysis/blob/main/Images/Img3.png?raw=true)

- Balanced Accuracy Score: 0.6512584051472337
- Precision: 0.99
- Recall Score: 0.45

---
**SMOTEENN**
![Img4](https://github.com/maddenc33/Credit_Risk_Analysis/blob/main/Images/Img4.png?raw=true)

- Balanced Accuracy Score: 0.5293318990697431
- Precision: 0.99
- Recall Score: 0.57

---
**BalancedRandomForestClassifier**
![Img5](https://github.com/maddenc33/Credit_Risk_Analysis/blob/main/Images/Img5.png?raw=true)

- Balanced Accuracy Score: 0.7885466545953005
- Precision: 0.99
- Recall Score: 0.87

---
**EasyEnsembleClassifier**
![Img6](https://github.com/maddenc33/Credit_Risk_Analysis/blob/main/Images/Img6.png?raw=true)

- Balanced Accuracy Score: 0.9316600714093861
- Precision: 0.99
- Recall Score: 0.94

---

## Summary
