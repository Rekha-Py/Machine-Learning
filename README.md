
# CLASSIFICATION ON WINE DATASET

These data are the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines. The dataset has been imported from sklearn dataset.

Number of instances are :178 (50 in each of three classes)
Number of Attributes: 13 numeric , predictive attributes and the class
Attribute Informtion:

-Alcohol

-Malic acid

-Ash

-Alcalinity of Ash

-Magnesium

-Total phenols

-Flavanoids

-Nonflavanoid phenols

-Proanthocyanins

-Color intensity

-Hue

-OD280/OD315 of diluted wines

-Proline

-class: 
-class_0
 
 -class_1
 
 -class_2
-Missing attribute value= None



##  Project Motivation
Tis project is focused on classification with wine data from scikit learn dataset.
## Installation
Python version 3.7.8

Python Libraries:

- sklearn.

- Pandas.

- numpy.

- seaborn

- matplotlib.
## Implementation
In this project DecisionTreeClassifier is used for classification.The data loaded from sklearn have been split into training and testing data.
Cost complexity pruning is done to reduce the overfitting by creating smaller tree. Accuracy is being measured before and after pruning.