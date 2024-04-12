# Regression

We have data `train.csv` on housing prices in a certain city. We have 80 variables (including textual, numerical, categorical nominal and cateogric ordinal) with 1460 observations. First we prepare the data - we study the distribution of the explanatory variable (housing prices). We study the distribution of numerical variables by calculating statistics and visualizing their distribution. We handle missing values. We develop separate tactics for each type of data to increase the chances of better results by using pipelines and transformers, among others.

After preparing the data, we divide our set into a training sample and a test sample. Then, using Linear Regression, Logsitic Regression, Random Forest Regression, Decision Tree Regression, SVM, Neural Netowork, LDA, KNN, LGBMRegressor, we look at how the models perform with our data using $R^2$, Mean Absolute Error, or standard deviation. Then, using GridSearchCV, we try to tune the parameters of some models to get better estimates. 

Finally, we subjectively choose the best regressor and predict the test data contained in the `test.csv` file 
