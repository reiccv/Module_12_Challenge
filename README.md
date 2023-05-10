# Module 12 Challenge

# Credit Risk Classification

Credit risk poses a classification problem that’s inherently imbalanced. This is because healthy loans easily outnumber risky loans. In this Challenge, you’ll use various techniques to train and evaluate models with imbalanced classes. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

# Table of Contents

-[Imports](#imports)

-[Instructions](##instructions)

-[Split the Data into Training and Testing Sets](##split the Data into Training and Testing Sets)

-[Create a Logistic Regression Model with the Original Data](##create a logistic regression model with the original data)

# Imports

![]()

## Instructions:

This challenge consists of the following subsections:

* Split the Data into Training and Testing Sets

* Create a Logistic Regression Model with the Original Data

* Predict a Logistic Regression Model with Resampled Training Data 


## Split the Data into Training and Testing Sets

Open the starter code notebook and then use it to complete the following steps.

1. Read the `lending_data.csv` data from the `Resources` folder into a Pandas DataFrame.

![]()

2. Create the labels set (`y`)  from the “loan_status” column, and then create the features (`X`) DataFrame from the remaining columns.

    > **Note** A value of `0` in the “loan_status” column means that the loan is healthy. A value of `1` means that the loan has a high risk of defaulting.  

![]()


3. Check the balance of the labels variable (`y`) by using the `value_counts` function.

![]()

4. Split the data into training and testing datasets by using `train_test_split`.

![]()

## Create a Logistic Regression Model with the Original Data

Employ your knowledge of logistic regression to complete the following steps:

1. Fit a logistic regression model by using the training data (`X_train` and `y_train`).

![]()

2. Save the predictions on the testing data labels by using the testing feature data (`X_test`) and the fitted model.

![]()

3. Evaluate the model’s performance by doing the following:

    * Calculate the accuracy score of the model.

    * Generate a confusion matrix.

    * Print the classification report.


![]()