# Predict Customer Churn

- Project **Predict Customer Churn** of ML DevOps Engineer Nanodegree Udacity

## Project Description
This is a project in Udacity's Machine Learning DevOps Engineer course. The instructor gives a notebook file that includes the data preparation code, eda, training, and model evaluation. The student's task is to convert these pieces of code into python files and write unit tests for each of those functions.

This code uses python 3.7.9

## Files and data description
This version of our code yield the following result using pylint and autopep8 commands

```
pylint churn_library.py

Your code has been rated at 9.91/10 (previous run: 9.91/10, +0.00)
```

```
pylint churn_script_logging_and_tests.py 

Your code has been rated at 9.60/10 (previous run: 9.60/10, +0.00)
```

## Creating virtual enviroment with conda
In order to run our code, first you need to install the exact packages provided in the requirement.txt. To avoid any missmatching between different projects, we create a new virtual env using the following command:

```
conda create -n churn_predict python=3.8
conda activate churn_predict
pip install -r requirements.txt
```

## Running Files
Running the library file using the following command.

```
(churn_predict)$ python churn_library
```

The following steps executed:
* Loading the dataset.
* Encoding the categorical data.
* Creating EDA figures and saving then into the ./images/eda.
* Performing the feature engineering on the data.
* Train the Random Forest and Logistic Regression models and save them into the ./models file, then save the roc curves under ./images/results/.
* Find the feature importance if the random forest model and saving image to ./images/results

Running the unit test file using following command.
```
(churn_predict)$ python churn_script_logging_and_tests.py
```
The following steps executed:
* Run unit test for each function in churn_library.py
* Write log for each unit test execution



