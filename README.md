# Binary Classification Assignment.
* Checked for null values and need for data transformation and data manipulation.
* No Null values found.
* All of the data was numeric.
* Checked skewness of features both via Fisher_Pearson standardised moment coefficient and graphically.
* Almost all the features were heavily skewed.
* Tried Log Transformation to reduce skewness but of no use.
* Via use of boxplot found that almost all the features had multiple outliers.
* We used trees based model because they are not that much affected by skewness of data.
* ANOVA F-test, Mutual Information Statistics were used for feature selection.
* Mutual Information Statistics generally used with tree based models.
* Applied feature scaling using StandardScaler.
* Applied k-fold cross validation. From the kfold method plotted a graph which showcases the importance of each feature viz-a-viz others.
* Did Hyper Parameter tuning. Constructed a pipeline and used GridSearchCV.
* Splitted the model into train and test set.
* Created a function that returns the column names which are most important as feature from ANOVA and Mutual Information Statistics method.
* Found with only 10 features that the accuracy was more than 91% with both ANOMA and Mutual Information Statistics method. Only 6 of these columns were common.
* Tried prediction with Decision Tree Classifier, Bagging Classifier.
* Could have used Boosting, XGBoost, Catboost classifiers also.
* Finally created two output files. One only with predited values. Other csv file has test feature's data also.
