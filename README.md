# Demystify Machine Learning Model Selection, a Step by Step Guide
 
Model selection in Machine Learning is selecting the best model for your data. Different models will perform differently on different data sets and potentially by a large margin. It's pretty common these days that gradient boosted trees are the [best performing models](https://www.quora.com/Why-is-XGBoost-among-most-used-machine-learning-method-on-Kaggle) for tabular data, such as [XGBoost](https://towardsdatascience.com/https-medium-com-vishalmorde-xgboost-algorithm-long-she-may-rein-edd9f99be63d), or the implementation in SciKit Learn. However, instead of always defaulting to a model such as XGBoost, it's important to evaluate the performance of different algorithms and see which one will perform the best for you.

Additionally, there can be some advantages to different models. For example, **Logistic Regression** can tell you the model's **coefficients**, allowing you to explain the impact of each feature on the final prediction. Bagged Tree Models like **RandomForest** can tell you the **Feature Importance** of each column in the model, similar to the coefficients of Logistic Regression.

Let's take a look at how to choose the best model across both a scoring metric of your choice as well as the speed of training. 

Read more here: https://www.dataknowsall.com/modelselection.html
