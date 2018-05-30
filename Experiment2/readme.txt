10-Fold cross Validation on HRF - 2 way ( HL,DR)
In k-fold cross-validation, the original sample is randomly partitioned into k equal size subsamples. Of the k subsamples, 
a single subsample is retained as the validation data for testing the model, and the remaining k-1 subsamples are used as 
training data. The cross-validation process is then repeated k times (the folds), with each of the k subsamples used exactly 
once as the validation data. The k results from the folds can then be averaged (or otherwise combined) to produce a single 
estimation. The advantage of this method is that all observations are used for both training and validation, and each 
observation is used for validation exactly once
