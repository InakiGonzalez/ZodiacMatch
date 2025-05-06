# ZodiacMatch

## Introduction
In this project I will analyze a dataset provided by Codecademy in order to put my recently aquired skills of ML and Data Science into practice. The data is from the online dating application OKCupid and I will be preparing, analyzing this data to create a machine learning model to predict the zodiac sign of a user given their characteristics.

## Libraries Used
Confusion Matrix, Matplotlib, Numpy, Pandas, Scikit-Learn, Seaborn

## Data Visualization and Data Engineering
First, I created some visualizations using Seaborn charts that gave me a solid first glance at how data is distributed in the dataset. After observing how different variables (age, sex, income, gender, diet habits, etc.) are distirbuted, I started to organize and clean my data. I observed there were a lot of missing values for some of the features as well as too many features in the whole dataset. Then, after selecting my predictors and my output variable, I was able to start the training/testing phase.

I began to consider which models would be good for this project and decided that KNN, Decision Trees and Logistic Regression would be good choices considering they are all classifiers but work in different ways. This would give me the opportunity to analyze the results from all the models and realize what makes one model better than the others for this specific case.


## Model Training and Testing
Having all my data ready to be used to train and test my models, I started to do so with Logistic Regression, then KNN and lastly Decision Trees. They all showed different outputs and scores on their predictions. This worked as a guide for finding the best model. However, we should be careful when pondering our results, because initially it appeared as if DTs were the best-performing model when it was actually overfitting.

Further tests and hyperparameter tuning showed that KNN was the overall best-performing model.

## Conclusion
This is the first Data Science & Machine Learning project I have done since finishing my first course on the same topic. It helped me a lot to put all the pieces together and figure out how to carry out a project of this nature properly. 
For next projects similar to this one, a good improvement would be the implementation of feature selection/elimination techniques to select only the most relevant ones, saving time and resources and potentially improving final results.
