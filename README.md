# Customer Churn Predictor
Experimented with various models to predict the customer churn in a telecommunication company.
Performed Exploartory Data Analsysis, Data Cleaning and acessed feature relevance to the target. 
Experimented with various techniques of data splitting such as random split, startified split and even K-fold cross validation while tinkering with various Classification  models such: Logistic Regression, Random forest, Standar Vector Machine(SVM),XGBoost,GradientBoost. Along with that, tried to optimise the models by performing PCA as well.
Evaluated performance via AUC score, ROC, Acuuracy, Precision, Recall etc.

The best performing model was a Logistic Regression Classifier where train and test data were split randomly with an AUC score:0.8621 and accuracy 0.82.
XGboost and Gradient Boost also closely followed with AUC scores and Accuracy of 0.8481 & 0.81 and 0.8488 & 0.8033 respectively with a stratified split dataset
