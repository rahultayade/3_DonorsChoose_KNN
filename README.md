# 3_DonorsChoose_KNN

### Assignment 3: Apply KNN

1.[Task-1] Apply KNN(brute force version) on these feature sets</br>

Set 1: categorical, numerical features + project_title(BOW) + preprocessed_essay (BOW)</br>
Set 2: categorical, numerical features + project_title(TFIDF)+ preprocessed_essay (TFIDF)</br>
Set 3: categorical, numerical features + project_title(AVG W2V)+ preprocessed_essay (AVG W2V)</br>
Set 4: categorical, numerical features + project_title(TFIDF W2V)+ preprocessed_essay (TFIDF W2V)</br>

2.Hyper paramter tuning to find best K

- Find the best hyper parameter which results in the maximum AUC value

- Find the best hyper paramter using k-fold cross validation (or) simple cross validation data

- Use gridsearch-cv or randomsearch-cv or write your own for loops to do this task


3.Representation of results
- Plot the performance of model both on train data and cross validation data for each hyper parameter.
- Once you find the best hyper parameter, you need to train your model-M using the best hyper-param. Now, find the AUC on test data and plot the ROC curve on both train and test using model-M.
Along with plotting ROC curve, you need to print the confusion matrix with predicted and original labels of test data points</br>

4.[Task-2]</br>
- Select top 2000 features from feature Set 2 using `SelectKBest` and then apply KNN on top of these features</br>
                               
- Repeat the steps 2 and 3 on the data matrix after feature selection

5.Conclusion
- You need to summarize the results at the end of the notebook, summarize it in the table format. To print out a table please using prettytable library.
