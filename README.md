### Dataset
The wine dataset(available in scikit-learn) is a popular dataset used for multinomial classification. It contains 13 float features and three different classes.
### Pipeline
The imputation is done via SimpleImputer and KNNImputer.
The numerical data is transformed using a scalar and a normalizer which are tuned using GridSearchCV.
### Metrics
**Accuracy score** : 97.22%  
**F1 score** : 1.00, 0.96, 0.96
