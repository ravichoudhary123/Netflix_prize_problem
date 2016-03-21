# Netflix_prize_problem
This is an implementation of Alternating Least Squares (ALS) algorithm to solve the Netflix Prize problem. A dataset of ~100,000 user-movie rating 'transactions' is the input. It is converted to a matrix (users by movies), and ALS is used to fill in null values of the matrix. RMSE function compares results against known rating values, predictions are outputted to a txt file.
'MAIN.py' is the python script; 
'train_predicts_test.txt' contains the output for running the algorithm on the training data, outputted in the form of testing data; 
'test_predicts_train.txt' contains the output for running the algorithm on the testing data, outputted in the form of training data; 
'train.txt' and 'testing.txt' are the datasets.
