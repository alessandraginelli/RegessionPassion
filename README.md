# RegressionPassion
Predictions of continuous variables using supervised learning models 

<br>

## 1. Business Problem
Discount Motors is a used car dealership in the UK. They want to lead the way in used cars.
Selling to customers who want the latest and greatest features, without the price tag of a brand new car.

The details in the data reflect the information given to potential buyers in the website adverts.
Buyers typically want to know the road tax of a used car, which varies based on a combination of year registered, emissions and fuel type, with Electric cars currently exempt from road tax.

The company will accept 1500$ of difference from optimal price. 

### 1.1 Data Information
The sales team has pulled some data from the website listings from the last 6 months. They haven’t told us if the cars sold or how long it took to sell if it did, we just know they were listed and the price they were listed at.

## 2. Solution Strategy

My solution to solve this problem will be the development of a data science project. This project will have a machine learning model which can predict used cars prices.

**Step 01. Data Description:** In this first section the data will be collected and studied. The missing values will be threated or removed (no missing value in this dataset). Finally, a initial data description will carried out to know the data. 

**Step 02. Data Filtering:** Data filtering is used to remove columns or rows that are not part of the business.

**Step 03. Exploratory Data Analysis:** The exploratory data analysis section consists of univariate and multivariate analysis using seaborn and matplotlib.pyplot. Correlation is studied and variables are transformed to perform better analysis. 

**Step 04. Data Preparation:** In this section, the data will be prepared for machine learning modeling: they will be transformed to improve models performances. These methods consist in encoding, oversampling, subsampling or rescaling.

**Step 05. Feature Selection:** After the data preparation, we select best columns to be used for the training of the machine learning model. This reduces the dimensionality of the database and decreases the chances of overfiting.

**Step 06. Machine Learning Modeling:** Training of the machine learning algorithms and prediction of the data. Cross validation is used for hyperparameters tuning and to reach better performances. Feature importance establishes most important features for each model. 

**Step 07. Conclusions:** This is the conclusion stage where we summarize the best results.  

**Step 08. Business Requirements:** In this step, KPIs are created to establish if the model is right for business questions. KPIs are evaluated to understand how good is the model selected. 

## 3. Models comparison

#### Linear Regression Model

|   RMSE   |  R2   |
|:----------------:|
|   0.103  | 0.955 | 


#### Random Forest Regression Model

|   RMSE   |  R2   |
|:----------------:|
|   0.092  | 0.965 |


## 4. Machine Learning Performance

The chosen model was **Random Forest** and it was tuned to improve their parameters and scores.

## 5. Business Results

Using the chosen algorithm, 94% of used cars prices are predicted with an error of maximum 1500$. 

## 6. Conclusions

The data is extremely clean and linear; the difference between models performace is small, so considering that linear regression model is way faster to train, it can still be considered.  
