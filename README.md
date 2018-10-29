# Class-Imbalance-Machine-Learning
We have taken the dataset from Credit Card Fraud.
This is a case of imbalanced dataset as there are many examples of the non-fraud class whereas the class that we have to predict is the fraud class.
If this was not the case the out of the box classifiers such as Logistic Regression, Support Vector Machines (SVMs) would well on these.
But on such datasets, where the ratio of majority : minority is 9:1.
The classifiers would although show accuracies of 80-90% but those would be generalized accuracies as it is just a count of how many samples were wrong out of the data the classifier was asked to predict.

Techniques:

Train Data
Testing Data


3 separate classifiers:
Multi Layer Perceptron (MLP)
Random Forest
K Nearest Neighbours


Sampling Techniques:
Undersamping
Oversampling
Synthetic Data Generation


Ensemble Model 1:(Original Data)
MLP + Random Forest + K Nearest → Logistric Regression

EnsembleModel2:(Sampled Data)
MLP + Random Forest + K Nearest → Logistric Regression

EnsembleModel3:(Sampled Data)
Naive Bayes
Linear SVM
Ada Boost → Logistic Regression












