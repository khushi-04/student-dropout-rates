# Student Dropout Rates
We explored a UCI database using exploratory data analysis (EDA), supervised machine learning, and unsupervised machine learning techniques. This project uses the 4.3.3 version of R-Studio. 

## UCI Database:
https://archive.ics.uci.edu/dataset/697/predict+students+dropout+and+academic+success

## Libraries used: 
* tidyverse
* gridExtra
* car
* MASS
* caret
* randomForest
* ROCR
* ggplot2
* viridis

## General Structure and Further Explanation
We did data cleaning and defined research questions. After doing, we did extensive EDA to decide which variables from the database we wanted to explore. 

Some EDA involves graphs, figures, and statistical analysis. In our statistical analysis, we performed different tests such as t-tests and correlation tests. We used ggplot to plot different variables. 

For supervised machine learning, I used a multiple logistic regression model. For unsupervised machine learning, I used a random forest model. To test these models, I used a variety of techniques, such as forwards and backwards selection, AIC and BIC scores, Cook's plot, multicollinearity, confusion matrices, and k-fold cross validation, and ROC curves. 
