# Practical Machine Learning Course Project (Coursera)

## Background
The data analyzed in this project comes from on-body movement measurements of people lifting weights (http://groupware.les.inf.puc-rio.br/har). Participants are asked to perform weight-lifting with the correct execution and four other ways that correspond to four different common mistakes. The goal is to predict which out of the five categories did one lift weight based on measurements from accelerometers attached to the belt, forearm, arm and dumbell.
## Method
Random Forest ('rf') and Stochastic Gradient Boosting Tree ('gbm') methods are used to build models. Cross validation is used to choose tuning parameters in each model. Details are described in the R markdown file `index.Rmd`.
## Summary
Using random forest and boosting algorith from the caret package and tuned the key parameters to our data, we could see that the two models could both achieve high accuracy and their predictions on the test data set we got from random forest and boosting models are the same.
