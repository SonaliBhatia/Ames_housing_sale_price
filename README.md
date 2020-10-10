# Project 2 - Ames Housing Data and Kaggle Challenge

This project has been developed to resolve the problem below.

Problem statement : Develop a model using different modeling techniques to help a group of Real Estate Investors to predict selling price for homes, defining relationship between the sale price and various features of the property.

All the code for project is present in Jupyter notebook  Third_attempt_Kaggle_Solution.ipynb

Data - There are 2 data sets that were used to develop this model. train.CSV and test.CSV. Datasets are available in Datasets folder.

Model generates a CSV file which was used for submission on Kaggle for Kaggle competition, file generated is called 'my_fifth_submission.CSV'.

Flow or steps model follows to generate Sale price.
1) Import data using panda's read_csv method.
2) Analyze data , perform any required clean up for data.
3) Impute all the null values , for this particular model all the null values are imputed with 0.
4) Perform exploratory data analysis to find co-relation between different numerical columns of the data set and target column.
5) Choose appropriate features for modeling.
6) This model uses Multiple linear regression to predict sale price for houses in Ames , Iowa
7) Feature engineering(Polynomial Features) is used to improve model performance.
8) Model is trained using train.csv and test.csv is used to test model performance on unseen data.
9) Model coefficients are used to find the relationship or impact of features on sale price.
