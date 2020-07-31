# DimensionalityReduction-PrincipalComponentAnalysis-Using-Python


This repository includes the code I have worked for reducing the dimensions in the dataset. Reducing the dimensionality is very important in the world of Machine Learning if we have thousands of variables

# Kaggle Competition

I have worked on PCA (for reducing the dimensions of the dataset) while submitting the predictions for Fraud Modeling (Kaggle competition) as the data contains more than 500 variables in total. I have used train set (train_identity and train_transaction) in the competition with many variables into reduced number of dimensions to build the ML algorithms for submission. Use of dimension reduction increases the accuracy rate by 4%.

The competition link can be found below:
https://www.kaggle.com/c/ieee-fraud-detection

![pca](https://user-images.githubusercontent.com/65406908/89065049-0d6c0100-d339-11ea-9e8c-61a0063c1f97.jpg)


# When should I use PCA?
If your answer is yes to the below questions- Consider to use PCA

Do you want to reduce the number of variables, but aren’t able to identify variables to completely remove from consideration?
Do you want to ensure your variables are independent of one another?
Are you comfortable making your independent variables less interpretable?


This repository contains notebook "PCA-Dimensionality Reduction.ipynb" with 2 steps below:

# PCA Steps in the Notebook code:

PCA Algorithm: Part 1- We are forcing the algorithm to use only 4 components

PCA Algorithm: Part 2- Building PCA to get optimal number of components that explains maximum variance
