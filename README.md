# Finding_Donors Project
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
