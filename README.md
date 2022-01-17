# NBA-Prediction-

## Objectives

• The goal of this project is to predict upcoming NBA game result based on team stats
and ELO Ratings. On our research we found that the already built predicting models
were using different features like FGA, FGM, 3ptPct, 3pA etc (other than Elo rating
and recent team performances) have low accuracy. So we are looking to develop a
model that used ELO ratings as well as other features to predict the game outcome as
the win % depends on the individual team performance as well

• To compare the players more easily based on their past performances we will use
different data visualizing techniques using tableau. By this we can sort or filter
players and rank them according to their various features.

## Methodology 

### Tools used:

• Google Colab

• Python

• Tableau Prep Builder - Data Cleaning and Pipelining

• Tableau Desktop - Data Analytics and Visualizations

• Microsoft Excel - Data Preparation

### Libraries used:

• Scikit Learn

• Seaborn

• Matplotlib

• Pandas

• NumPy

## Observation and Finding

We trained our features using Logistic Regression Classifier And Random Forest 
Classifier with Randomized search CV and Grid Search CV and the following were the 
accuracies obtained

### Accuracy of models:

• logistic regression classifier –65.8%

• logistic regression classifier with hyperparameter tuning using Random Search CV - 66.8%

• logistic regression classifier with hyperparameter tuning using Grid Search CV - 66.8%

• Random Forest classifier – 65.8%

• Random Forest classifier with hyperparameter tuning using Random Search CV - 66.8%

• Random Forest classifier with hyperparameter tuning using Grid Search CV - 65.4%

After compiling the program for Logistic Regression and Random Forest Classifier on 
the available team data, we get accuracy of 65.4%–66.8% for win prediction. The 
Highest testing accuracy is 66.8% and it is achieved by using Random Forest 
Classifier Model with hyperparameter tuning using Random Search CV.

• By building visualization on tableau, we are able to sort and filter players according 
to their various features like number of matches played, accuracy of goals etc. 
