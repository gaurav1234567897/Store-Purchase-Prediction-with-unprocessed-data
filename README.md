# Store-Purchase-Prediction-with-unprocessed-data
Store Purchase Prediction with unprocessed data
Write up:

Assumptions:
The effect of feature STATE is assumed in the classification by converting them into their frequency of occurrences and then normalizing to minimize the presence of large number of features due to large no. of unique values for feature STATE.
Data is assumed to be normally distributed for using Logistic Regression Model.
Specific Insights from Data:
•	Impact of LOYALTY_PROGRAM for decision of customer PURCHASE is not seen as an important feature than perceived.
•	On drawing histogram of AGE feature it is found to have 2 distinct distributions one of high age section and one of low age section this ,clearly indicates more purchase by low age section and more focus should be on products for low age group.  
•	Maximum No. of buyers are only from few STATE like Maharashtra, etc.
•	Dataset is highly unbalanced hence, required to balance using SMOTE.
•	Feature PAST_PURCHASE is highly skewed and have outlier hence, have to use log transformations.
•	Large No. of missing values are present hence, have to impute values using mode for the categorical variables.
•	Large No. of blank spaces in columns are replaced by their modes.
•	Random Forest classifier works better than Logistic Regression for the dataset.
•	PAST_PURCHASE and AGE are seen as important feature for the classification.
