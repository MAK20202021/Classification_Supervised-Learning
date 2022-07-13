# Classification_Supervised-Learning

Classification is a Supervised Learning algorithm where outcome is a category. This algorithm learns from the labeled data where features can be quantified. Applications of this algorithm are customer spending, customer churn, fraudulent transaction detection using customer characteristics, location, Ip address. In this exercise, we have focused on the classification error matrix such as accuracy measurement, confusion matrix, Receiver Operating Characteristics (ROC), Precision and Recall. ROC is better for balanced classes and Precission - Recall is better for imbalanced classes. ROC plots the true positive rate (Sensitivity) of a model vs its false positive rate (1- sensitivity). 
Here we used Human Activity Recognition with smart phones database which are related to Activity of Daily Living (ADL) such as walking, walking upstairs, walking downstairs, sitting and laying.

The following information is provided for each record in the dataset:
-Triaxial acceleration from the accelerometer (total acceleration) and the estimated body acceleration
-Triaxial Angular velocity from the gyroscope
-A 561-feature vector with time and frequency domain variables
-The activity label

The objective is to classify the activities the participants performed into one of the six following categories: walking, walking upstairs, walking downstairs, sitting, standing, and laying.

We needed to use LabelEncoder to label the activity column to use the scikit learn model.


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
After completing this exercise, I understand how we can build a.
