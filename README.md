## **Mobile Phone Price Prediction**

This project aims to predict the price of mobile phones based on their specifications using various machine learning models. The dataset includes features such as Model, Colour, Rear Camera, Front Camera, Processor, and Price.

Dataset The dataset used in this project contains the following features:

Model: The model of the mobile phone.

Colour: The color of the mobile phone.

Rear Camera: Specifications of the rear camera.

Front Camera: Specifications of the front camera.

Processor: The type of processor used in the mobile phone.

Price: The price of the mobile phone (target variable).

Features

The following preprocessing steps were performed on the dataset:

Data Cleaning: Handling missing values and removing irrelevant features.

Encoding Categorical Features: Converting categorical features into numerical representations.

Feature Scaling: Normalizing/standardizing numerical features.

Feature Engineering The following feature engineering steps were applied:

Handling Missing Values: Features with a high ratio of missing values were removed.

Encoding: Categorical features were encoded using appropriate techniques.

Model Training Several machine learning models were trained and evaluated:

**Linear Regression

Decision Tree

Random Forest

XGBoost

Results

The performance of the models was evaluated using metrics such as Mean Squared Error (MSE) and R² Score. The results showed that Random Forest and XGBoost were the top performers based on the testing R² scores, indicating that they are highly effective and generalize well to unseen data.
