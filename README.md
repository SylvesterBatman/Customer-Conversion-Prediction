# Customer-Conversion-Prediction
Import the nneded requirements liks NumPY, Pandas, Pyplot to visualize the given data and seaborn.

Import the csv file by using of pandas.

Apply the 6 jars of Machine Learning. 

i) Clean the data

ii) Do the Exploratory Data Analysis with pyplot to visualize the data in graph.

iii) Encode the data in numerical values. Since the given data is Classification Imbalanced data,
        Use Label Encoding.

iv) Split the data as 20% to test data and remaining as train data to apply ML model

v) Import DecisionTreeClassifier to fit the model.

vi) Evaluate the model using Accuracy score and the result is 60, which is not a good evaluation        value

Since it is imbalance dataset, using of Confusion matrix shows that Dataset belongs to the single class.

Import SMOTEENN to fit the model (Over Sampling followed by under sampling) and to balance the imbalanced dataset.

Apply the Ensemble Learning Model to fit the model in LogisticRegression, DecissionTreeClassifier and KNeighborsClassifier.

Use Auroc Score as Evaluation metric and find the best model.

Import XGBoost to find the cross-validation score. The highest CV score will be considered as the best score of the given model.
