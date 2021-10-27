# 20191COM0045_nasscom
Linear regeression is a classification of supervised learning.
Linear regression is a relationship between dependent variable and one or more independent variable. In this project we are gonna determine the quality of red wine using linear regression. Here the quality of wine will be the dependent variable and the indepedent variable would be fixed acidity, volatile acidity, citric acid, residual sugar,chlorides, free sulfur dioxide, total sulfur dioxide, density,pH, sulphates,alcohol(but later we'll filter out insignificant variables).
The following are the brief steps:
* import the necessary packages i.e numpy,pandas etc.
* upload the data to colab and convert it into Dataframe,find the info,description and view the data.
* find the missing values in the data using isnull() method.
* Drop the duplicates in the data using drop_duplicates method.
* Since it is a supervised learing define X and Yfeatures and Split the data into training and testing dataset using train_test_split from sklearn.model_selection.
* Explore the train dataset by describing and visualisng (pairplot,correlation matrix)
* Rescale the train dataset by using scaler.fit_transform
* Pop the quality attribute from the train dataset.
* Import LinearRegression() from sklearn.linear_model.
* Perform VIF(Variation Inflation Factor is an algorithm used to keep the model as simple as possible),its a iterative process,for every model have a view of params and summary.
* The error terms follow normal distribution.
* Apply Scaling on test sets.
* plot a scatter plot on y_test vs y_pred.
* Find the r^2 and adjusted r^2 of test dataset and compare those values with train dataset.
* Find Mean Absolute Error, Mean Squared Error and Root Mean Square Error.
