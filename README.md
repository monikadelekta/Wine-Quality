# Wine-Quality

A simple wine quality classifier using the Python package [Scikit-Learn](https://scikit-learn.org/stable/). 

Data used is taken from Kaggle challenge to classify [Red Wine Quality](https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009).

The code is a simple use case that showcases the use of a Random Forest Classifier, Support Vector Machine and Neural Network. 

## Random Forest Classifier 

This is an supervised learning approach that uses an ensemble of many decision trees with a random element to prevent overfitting. It can be used for both classification and regression. 

**Advantages: **

* It is more robust than decision trees which are prone to overfitting
* You can pull out the relative feature importance to know which variables to discard/keep

**Disadvantages: ** 

* Normally quite slow - in this case the dataset is small so this does not apply
* More difficult to interpret in comparison to decision trees

Documentation of the random forest classifier can be found [here](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html).

## Support Vector Machine

SVM is an algorithm that use hyperplanes in and N-dimensional space to classify points. It can be used for both classification and regression. Classification is completed by finding the hyperplane that separates the two classes.

**Advantages: **

* Memory efficient
* Still useful when there are more dimensions than samples

**Disadvantages: **

* Kernel functions are crucial to prevent overfitting

You can find the documentation fro SVM's [here](https://scikit-learn.org/stable/modules/svm.html).

## Neural Network - Multi Layer Perceptron

A supervised learning approach where given a set of features and a target it can learn a non-linear function approximator for classification/regression. 

**Advantages: **

* It can learn non-linear models


**Disadvantages: **

* Requires a lot of tuning
* Sensitive to feature scaling

Documentation for MLP can be found [here](https://scikit-learn.org/stable/modules/neural_networks_supervised.html).
