# Mercedes-Benz-Greener-Manufacturing-Project

📝 The aim of the project is to reduce the time that cars spend on the test bench. You will work with a dataset representing different permutations of features in a Mercedes-Benz car to predict the time it takes to pass testing. Optimal algorithms will contribute to faster testing, resulting in lower carbon dioxide emissions without reducing Daimler’s standards.

## 📈Steps Performed:

## Step 1: Import the required libraries

Step 1.1: linear algebra

Step 1.2: data processing

Step 1.3: for dimensionality reduction

## Step 2: Read the data from train.csv

Step 2.1: let us understand the data

Step 2.2: print few rows and see how the data looks like

## Step 3: Collect the Y values into an array

Step 3.1: seperate the y from the data as we will use this to learn as the prediction output

## Step 4: Understand the data types we have

Step 4.1:iterate through all the columns which has X in the name of the column

## Step 5: Count the data in each of the columns

## Step 6: Read the test.csv data

Step 6.1: remove columns ID and Y from the data as they are not used for learning

## Step 7: Check for null and unique values for test and train sets 

## Step8: If for any column(s), the variance is equal to zero, then you need to remove those variable(s)

Step 8.1: Apply label encoder

## Step 9: Make sure the data is now changed into numericals

## Step 10: Perform dimensionality reduction

Step10.1: Linear dimensionality reduction using Singular Value Decomposition of the data to project it to a lower dimensional space.

## Step 11: Training using xgboost

## Step 12: Predict your test_df values using xgboost
