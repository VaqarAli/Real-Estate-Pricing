# Real-Estate-Pricing

Price of a property is one of the most important decision criterion when people buy homes. Real state firms need to be consistent in their pricing in order to attract buyers . Having a predictive model for the same will be great tool to have, which in turn can also be used to tweak development of properties, putting more emphasis on qualities which increase the value of the property.

We have two datasets, housing_train.csv and housing_test.csv. We'll use data housing_train to build predictive model for response variable "Price". Housing_test data contains all other factors except "Price", we'll predict that using the model that we'll be developing.

We have used Pearson correlation coefficient to check the correlation between predicting and target variable. We've used 2 models to predict the target variable viz. Linear Regression and XGBoost and we'll see the difference amongst their performances.
