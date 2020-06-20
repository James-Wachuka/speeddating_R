###### Speed_dating
A classification problem in R for determining the possibility of a second date based on the outcome of the first date.A data set for this task is provided:*speeddating.csv*

###### Data pre-processing 
The target variable *second_date* was created for use in this task.*Amelia* function was used to impute the missing values.Non-numeric values have been encoded for ease of use in analysis and modelling.

###### Exploratory Data Analysis
decision trees, box plots, barcharts, jitter plots were used to analyse data, with the aim of discovering the underlying information.A detailed analysis is provided in the R notebook.

###### Feature selection, model building and Evaluation
Random forest was preferred for feature selection  as compared to correlation matrix because it gives a simpler result that is easy to study.Logistic regression,KNN and Bayesian Classifier were used for this task with random sampling of rows.The models were evaluated based on AUC score.

###### speeddating.nb.html
This R notebook contains the detailed presentation of the whole task.