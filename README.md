# project-2-kings_county-house-prediction
## overview
* the project shows the collection of data from a open website, and use that data to create a regression model. this regression model will be validated according the the varibal trend and then used for predicting the price. All this will be done by performing various regression techniques.
## data
* the dataset used in this project belongs to kaggle.com
* it contains a dataframe with various columns sch as price, which is our target varibale, and sqft size for all dimensions, floors, renovation year, built year etc.
## step by step procss for the project
### importing data set
### cleaning
* the data set contains empty blocks, whihc are removed in the first part of code block.
* the values approching to infinity are also removed
* outliers are detected and are removed
* various columns are dropeed as not required.
## modeling
* the first model is created by stats.model code.
* which represent the correleation among vsriables.
* the model was rejected as it shows abnormal behaviour.
### second model
* this creared by train and test split code
* the ratio for this split is 3:7
* the model is better than previous one
* coefficients are better
* r2 value is good
### cross-validation
* the seciond model is tested by concept using cross validation.
* both scores are almost same but not identical.
### third(final mode)
* this is created by train test split with ratio 2:8
* coefficients are much better
* visualization supports the model
* prediction is significant
### cross-validatipn
the c-v score is far better
