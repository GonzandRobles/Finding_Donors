python 3.6

# Finding Donors Project
In this project, we are going to work with a fictitious charity organization located in Silicon Valley.
The goal of the creation of this fictitious company is to provide financial support to pleople who are interested
in learning machine learning.

# Keypoints

- CharityML determined that every donation they received came from someone that was making more than $50,000 annually.

# Installations

### Data manipulation packages:

- pandas
- numpy
- time
- IPython.display -> allows the use of display() for DataFrames
- visuals -> supplementary visualization code visuals.py

### Normalizing Numerical Features:

- sklearn.preprocessing import MinMaxScaler -> transforms features by scaling each feature to a given range.

### Train Test split data:

- sklearn.cross_validation import train_test_split -> Split arrays or matrices into random train and test subsets

### Evaluating Model Performance:

- sklearn.metrics import accuracy_score, fbeta_score:
  fbeta = The F-beta score is the weighted harmonic mean of precision and recall, reaching its optimal value at 1 and its               worst value at 0.
  
### Model Selection:
  
- sklearn.svm import SVC -> Suport Vector Classifier
- sklearn.tree import DecisionTreeClassifier -> Decision Tree Classifier
- sklearn.ensemble import RandomForestClassifier -> Random Forest Classifier

### Implementation model tuning packages:

- sklearn.metrics import make_scorer -> make a scorer from a performance metric or loss function.
- sklearn.model_selection import GridSearchCV -> process the hyper parameter tuning to determine the optimal values
- sklearn.ensemble import AdaBoostClassifier -> adaptive boosting used in conjunction with many other types of learning algorithms to improve performance

### Functionality for cloning a model  

- sklearn.base import clone -> for cloing the model and use a subset of all the available features in the data and compare 
models.

# Project Analysis

### Getting Started:

Finding Donors starts with a brief description of the company, the target, the dataset origin and the article by Ron Kohavi from where the project it's inspired.

### Exploring the Data

This part is designated for the data exploration: number of values in the dataset, null values, featureset exploration.

### Data Preparation

Transforming skewed continuous features, normalizing numerical features, data preprocessing (get dummies), shuffle and split data.

### Evaluating Model Performance

Implementation if 3 different algorithms for comparison purposes through the creation of a training and predictive pipeline.

### Improving Results

In this final section, the best out of three supervised learning models is selected. Then we perform a grid search optimization for the model over the entire training set (X_train and y_train) by tuning at least one parameter to improve upon the untuned model's F-score.

### Conclusions

Final conclusions of why of the decision taken on which model we picked
