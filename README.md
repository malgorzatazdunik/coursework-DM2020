# DM2020CSWK
Data Mining Assignment


PART 1:

This task is based on the Sonar real data. Several objects which can be rock or metal cylinders are scanned on different angles and under different conditions, with sonar signals. 60 measurements are recorded per columns for each object (one record per object) and these are the predictors called A1, A2, …, A60. The label associated with each record contains the letter "R" if the object is a rock and "M" if it is metal cylinder, and this is the outcome variable called Class.

Two datasets are provided: a training dataset in the sonar_train.csv file, and a test dataset in the sonar_test.csv file.

Task: write a Python code implementing the Nearest Neighbour algorithm (not kNN), with the Euclidian and Manhattan distances. The code will classify each record from the test dataset based on the training dataset, and then will calculate and display the accuracy of the predictions on the test dataset based first on the Euclidian distance and then on the Manhattan distance.

The code, comments, explanations and results are provided in the Jupyter notebook Part1.

PART 2:

This task is based on a real credit risk data, and is to predict not-credible and credible credit card clients. More precisely, the task is to predict a response variable Y which represents a credit card default payment (Yes = 1, No = 0), using the 23 predictor variables as follows:

X1: Amount of the given credit (NT dollar): it includes both the individual consumer credit and his/her family (supplementary) credit.
X2: Gender (1 = male; 2 = female).
X3: Education (1 = graduate school; 2 = university; 3 = high school; 4 = others).
X4: Marital status (1 = married; 2 = single; 3 = others).
X5: Age (year).
X6 - X11: History of past payment. One tracked the past monthly payment records (from April to September, 2005) as follows: X6 = the repayment status in September, 2005; X7 = the repayment status in August, 2005; . . .;X11 = the repayment status in April, 2005. The measurement scale for the repayment status is: -1 = pay duly; 1 = payment delay for one month; 2 = payment delay for two months; . . .; 8 = payment delay for eight months; 9 = payment delay for nine months and above.
X12-X17: Amount of bill statement (NT dollar). X12 = amount of bill statement in September, 2005; X13 = amount of bill statement in August, 2005; . . .; X17 = amount of bill statement in April, 2005.
X18-X23: Amount of previous payment (NT dollar). X18 = amount paid in September, 2005; X19 = amount paid in August, 2005; . . .;X23 = amount paid in April, 2005.

Two datasets are provided: a training dataset in the creditdefault_train.csv file, and a test dataset in the creditdefult_test.csv file.

Task: build the best predictive model by tuning models using cross validation on the training dataset with each of the following algorithms (seen in class): kNN, decision trees, Random Forest, Bagging, Boosting, and SVM. Out of the models tuned with the above algorithms, select the best model and clearly justify your choice, and evaluate its performance on the test set.

The coding, comments and explanations are provided in the Python Jupyter notebook called Part2, which also includes the results.
