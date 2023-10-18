# Random Forest and Decision Tree

## Description

### For this project, we will be exploring publicly available data from [LendingClub.com](www.lendingclub.com). Lending Club connects people in need of money (borrowers) with people who have money to invest (investors). As an investor, you would prefer to invest in individuals who have shown a profile with a high probability of paying it back. We will attempt to create a model that helps predict this.

### We will use loan data from 2007-2010 and try to classify and predict whether the borrower paid the loan in full. You can download the data from [here](https://www.lendingclub.com/info/download-data.action) or simply use the provided CSV. It is recommended to use the provided CSV since it has been cleaned of any missing values.

## Libraries required for development:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn (sklearn)

## Script Explanation:

### This script is related to loan approval data for customers, and the question to be resolved by analyzing various customer data is:

### Is the customer eligible to receive the loan and meet the payment deadlines, avoiding losses for the company?

### The analysis model used includes Random Forest, Decision Tree, and even the combination of these two models, leading to the following conclusions:


* When considering only accuracy, and if we consider when the model indicates the customer is **eligible** to receive the money, the **Random Forest** model performed better.
* However, the accuracy for when the customer is **not eligible** to receive the money is very low. In such cases, the **Decision Tree** model is a good alternative when both relative accuracy for accepting or declining the loan is desired.

