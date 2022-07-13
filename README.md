# Classification_Supervised-Learning

Classification is a Supervised Learning algorithm where outcome is a category. This algorithm learns from the labeled data where features can be quantified. Applications of this algorithm are customer spending, customer churn, fraudulent transaction detection using customer characteristics, location, Ip address. In this exercise, we have focused on the classification error matrix such as accuracy measurement, confusion matrix, Receiver Operating Characteristics (ROC), Precision and Recall. ROC is better for balanced classes and Precission - Recall is better for imbalanced classes. ROC plots the true positive rate (Sensitivity) of a model vs its false positive rate (1- sensitivity). 
We will use a customer churn dataset from the telecom industry, which includes customer data such as long-distance usage, data usage, monthly revenue, types of offerings, and other services purchased by customers. We are using the subset of customers who have phone accounts. Since the data includes a mix of numeric, categorical, and ordinal variables, we will need to do some preprocessing. 

The objective is to predict customer churn rates utilizing different classification models.

At the beginning, We will need to do details analysis of the dataset to dentify which variables are binary, categorical and not ordinal, categorical and ordinal, and numeric. The non-numeric features will need to be encoded using methods such as LabelEncoder.


## Acknowledgement
This exercise is for [IBM Machine Learning Professional Certificate Program](https://www.coursera.org/professional-certificates/ibm-machine-learning?).
Thanks to Coursera and IBM for arranging this exercise to strengthen our knowledge. 
## Installation
This exercise needs Anaconda package(Anaconda3), Jupyter Notebook (6.1.4).

## File Description
The source codes are as follows:
- Medicine_effect.ipynb
- Medicine_effect.html

## Discussion
After completing this exercise, I understand how we can build a classification algorithm based model such as Logistic regression, KNN, SVM.
