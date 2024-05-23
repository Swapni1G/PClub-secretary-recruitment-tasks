
# Machine Learning

This project is based on predicting lung capacity volumes as a function of various parameters such as gender, age, height, practises such as smoking, and whether the child birth is Caesarean or not.


## Dataset
    Firstly, I found a dataset at kaagle for tidal volume of lungs.
    (https://www.kaggle.com/datasets/radhakrishna4/lung-capacity)
    Kaggle is a data science community under google, and has a vast number of datasets.

## Implementation
    Then I :
    1. Read the dataset into a dataframe object, 
    2. Converted string values of "yes", "no", "male", "female" to 0 or 1 using map function.
    3. Divided the data into training and testing data, with testing data as 20 % of the total number of datapoints, using "train_test_split" function.
    4. Then we trained the model for minimising the cost function (mean of square deviations) using "LinearRegression" function on the training data.
    5. After that we tested our model on testing data which gave us a good accuracy of >85%.