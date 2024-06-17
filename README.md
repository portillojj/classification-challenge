# classification-challenge
Module 13 Challenge

## Background
Let's say you work at an Internet Service Provider (ISP) and you've been tasked with improving the email filtering system for its customers. You've been provided with a dataset that contains information about emails, with two possible classifications: spam and not spam. The ISP wants you to take this dataset and develop a supervised machine learning (ML) model that will accurately detect spam emails so it can filter them out of its customers' inboxes.

You will be creating two classification models to fit the provided data, and evaluate which model is more accurate at detecting spam. The models you'll create will be a logistic regression model and a random forest model.

## Files
Download the following files to help you get started:

## Before You Begin
Before starting the assignment, be sure to complete the following steps:
   - [x] Create a new repository for this project called `classification-challenge`. **Do not add this homework assignment to an existing repository.**
   - [x] Clone the new repository to your computer.
   - [x] Inside your local Git repository, add the starter file `spam_detector.ipynb` from your file downloads.
   - [x] Push these changes to GitHub or GitLab.

## Instructions

This challenge consists of the following subsections:

- Split the data into training and testing sets.
- Scale the features.
- Create a logistic regression model.
- Create a random forest model.
- Evaluate the models.

## Split the Data into Training and Testing Sets
1. Read the data from [https://static.bc-edx.com/ai/ail-v-1-0/m13/challenge/spam-data.csv] into a Pandas DataFrame.
2. In the appropriate markdown cell, make a prediction as to which model you expect to do better.
3. Create the labels set (`y`) from the “spam” column, and then create the features (`X`) DataFrame from the remaining columns.

**NOTE**
A value of 0 in the “spam” column means that the message is legitimate. A value of 1 means that the message has been classified as spam.

4. Check the balance of the labels variable (`y`) by using the `value_counts` function.
5. Split the data into training and testing datasets by using `train_test_split`.

## Scale the Features

1. Create an instance of `StandardScaler`.
2. Fit the Standard Scaler with the training data.
3. Scale the training and testing features DataFrames using the transform function.

## Create a Logistic Regression Model

Employ your knowledge of logistic regression to complete the following steps:

1. Fit a logistic regression model by using the scaled training data (`X_train_scaled` and `y_train`). Set the random_state argument to 1.
2. Save the predictions on the testing data labels by using the testing feature data ('X_test_scaled') and the fitted model.
3. Evaluate the model’s performance by calculating the accuracy score of the model.

## Create a Random Forest Model

Employ your knowledge of the random forest classifier to complete the following steps:

1. Fit a random forest classifier model by using the scaled training data (`X_train_scaled` and `y_train`).
2. Save the predictions on the testing data labels by using the testing feature data (`X_test_scaled`) and the fitted model.
3. Evaluate the model’s performance by calculating the accuracy score of the model.

## Evaluate the Models

In the appropriate markdown cell, answer the following questions:
1. Which model performed better?
2. How does that compare to your prediction?

## Badges

## Visuals

## Installation

## Usage

## Support
Some of the code on this assigment was done with the help of a bootcamp tutor.

## Roadmap

## Contributing

## Authors and acknowledgment
1. Reference material - [PEP 8 – Style Guide for Python Code](https://peps.python.org/pep-0008/)
2. Python HOWTOs - [https://docs.python.org/3/howto](https://docs.python.org/3/howto/index.html)
3. Markdown Guide -[Markdown Guide](https://github.com/mattcone/markdown-guide/tree/master)
4. This site was built using [GitHub Pages](https://pages.github.com/)


## License


## Project status
- Submitted for grading (06.17.2024)

## Footnotes