Marketing Campaign Analysis for Gold Membership

Introduction
This project aims to enhance the efficiency of a marketing campaign for a retail chain's Gold Membership by leveraging data from a previous campaign. The main objective is to create a predictive model to prioritize customers likely to respond positively and identify key demographic and behavioral factors influencing their response.

Methodologies
Data Preprocessing:
Date format conversion for consistency.
Imputation of missing values in the "Income" column based on the median income per education level.
Exploration and cleaning of categorical variables, particularly "Marital Status" and "Education Level".
Age calculation and customer tenure derived from date of birth and enrollment date.

Exploratory Data Analysis:
Distribution analysis of the target variable.
Correlation matrix to understand relationships between variables.
Percentage plot of recency bins and average income by response.

Feature Engineering:
One-hot encoding of categorical variables ("Education" and "Marital Status").
Train-test split with an 80-20 ratio, ensuring stratified sampling due to imbalanced target variable.
Standard scaling of features.

Modeling:
Regular classification using Logistic Regression and Gradient Boosting Trees.
Weighted classification to address class imbalance, adjusting weights to favor the minority class.
Evaluation using ROC curves and recall for the positive response class.


This project leverages data from previous marketing campaigns to build predictive models prioritizing customers likely to respond positively to a retail chain's Gold Membership offer. Key insights reveal that high spenders on alcohol and meat products, as well as in-store shoppers, are prime targets, allowing for more efficient and tailored marketing strategies.
