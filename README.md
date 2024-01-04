
Medical Cost Prediction
This project aims to predict the medical costs of individuals based on their personal information and health conditions.
The project uses a linear regression model to fit the data and evaluate the performance.

Dataset
The dataset contains 1,339 medical insurance records from Kaggle’s Medical Cost Personal Datasets. The target variable is charges,
which represents the individual medical costs billed by health insurance. The features include:

age: age of primary beneficiary
sex: insurance contractor gender, female, male
bmi: body mass index, providing an understanding of body
children: number of children covered by health insurance / number of dependents
smoker: smoking status, yes or no
region: the beneficiary’s residential area in the US, northeast, southeast, southwest, northwest

The project explores the data with descriptive statistics and visualizations. It also performs some data preprocessing steps such as encoding categorical variables and scaling numerical variables. The project then splits the data into training and testing sets, and trains a linear regression model using scikit-learn. The model is evaluated using the coefficient of determination (R2) and the root mean squared error (RMSE). 
