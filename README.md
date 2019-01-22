# RegressionAnalysis1
The original college data was analyzed using linear regression model in R. 
In the first model, the "median" income was considered as the response, while the "major_category "and all the "perc_"s were considered as the predictors. Through summary and anova analysis, it was found that the p-value for the "major_category" was greater than 0.05 (>0.05). Therefore, the "major_category" did not have significant effect on the median of income.
Then, the same type of model was applied to "p75th" and "p25th". The p-values for the "major_category" were still greater than (>0.05), which showed no significant association.

Another type of regression model was applied to the data too. In this model, "major_category" was the only predictor, while "median", "p75th", and "p25th" were considered as the response for each model. Similar results were obtained through summary and anova analysis. No significant association was found between the major category and the income.
