## House Price Prediction

This project aims to predict house prices using a linear regression model. The following steps were performed:

Importing Dependencies: Necessary libraries such as pandas, numpy, matplotlib, seaborn, and scikit-learn were imported.

Data Collection and Preprocessing: The Housing.csv dataset was loaded into a pandas DataFrame. The shape, missing values, and data types were inspected.

Handling Outliers: Outliers in the 'price' and 'area' features were identified using boxplots and handled by capping them at the IQR boundaries.

Encoding: Categorical features were converted into numerical features using Label Encoding and One-Hot Encoding.

Scaling: Numerical features were scaled using MinMaxScaler.

Separating Data and Labels: The data was split into features (X) and the target variable (Y).

Training the Model: A Linear Regression model was trained on the training data.

Evaluation: The model was evaluated on both training and testing data using R-squared, Mean Absolute Error (MAE), and Mean Squared Error (MSE). Residual plots were also generated.

Coefficients: The coefficients of the trained model were inspected to understand the impact of each feature on the price prediction.
