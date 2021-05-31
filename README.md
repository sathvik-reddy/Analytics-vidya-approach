# Analytics-vidya-approach
1)Have done extensive EDA on the dataset,dissecting every column with respect to the target variable

2)Found that there are NaN values,and replaced it with the string 'NaN' so catboost can perform well on it

3)Left all the categorical variables as it is without encoding them as catboost performed well with unencoded data when compared to encoded data

4)split the data into train and test and worked on hyper-parameter tuning ,from which learning rate=0.01 and subsample =0.9 seemed to increase 
the accuracy when compared to default settings on different combinations of train-test

5)Finally trained the model on the whole data and then made predictions on the test data which gave out accuray of 0.8730684318
