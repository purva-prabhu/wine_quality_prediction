## Wine Quality Prediction
Predicting the Quality of Red Wine using Machine Learning Algorithm.

# Introduction
For this project, I used Kaggle’s Red Wine Quality dataset to build various classification models to predict whether a particular red wine is “good quality” or not. Each wine in this dataset is given a “quality” score between 0 and 10. For the purpose of this project, I converted the output to a binary output where each wine is either “good quality” (a score of 7 or higher) or not (a score below 7). The quality of a wine is determined by 11 input variables:

    1) Fixed acidity
    2) Volatile acidity
    3) Citric acid
    4) Residual sugar
    5) Chlorides
    6) Free sulfur dioxide
    7) Total sulfur dioxide
    8) Density
    9) pH
    10) Sulfates
    11) Alcohol
    
    
# Machine learning model:
# Random Forest

Random forests are an ensemble learning technique that builds off of decision trees. Random forests involve creating multiple decision trees using bootstrapped datasets of the original data and randomly selecting a subset of variables at each step of the decision tree. The model then selects the mode of all of the predictions of each decision tree. By relying on a “majority wins” model, it reduces the risk of error from an individual tree.

# Conclusion

The usage of this analysis will help to understand whether by modifying the variables, it is possible to increase the quality of the wine on the market. If you can control your variables, then you can predict the quality of your wine and obtain more profits. Plotting graphs of relation b/w different variables is the basic step to determine the factors that have larger impact and to work upon those factors.
