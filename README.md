# Sales Prediction Using Regression Analysis

This project focuses on predicting sales based on marketing spend using various regression techniques. The dataset consists of marketing spend (in million dollars) and corresponding sales (in million dollars). Here's a brief overview of the project:

## Objective
The main objective is to build regression models to predict sales based on the amount spent on marketing.

## Data Preparation and Exploration
- Imported necessary libraries such as NumPy, Pandas, Matplotlib, Seaborn, and scikit-learn.
- Loaded the dataset and visualized it using scatter plots to understand the relationship between marketing spend and sales.

## Data Preprocessing
- Scaled the data using MinMaxScaler to bring the features within the range of 0 to 1.

## Model Building
- Built a simple linear regression model to predict sales based on marketing spend.
- Evaluated the model's performance using metrics such as R-squared, Root Mean Squared Error (RMSE), and Residual Sum of Squares (RSS).

## Polynomial Regression
- Implemented polynomial regression with a degree of 5 to capture non-linear relationships.
- Plotted the polynomial regression curve along with the original data.

## Ridge Regression
- Applied Ridge Regression with different values of the hyperparameter lambda to introduce regularization.
- Visualized the effect of regularization on the model's coefficients.

## Lasso Regression
- Implemented Lasso Regression with various values of lambda to perform feature selection.
- Examined the impact of L1 regularization on the model's coefficients.

## Comparison of Models
- Compared the coefficients of polynomial, ridge, and lasso regression models.
- Evaluated the performance of each model using R-squared score.

## Conclusion
This project demonstrates the application of different regression techniques for sales prediction. It highlights the importance of selecting appropriate models and regularization techniques based on the dataset characteristics.

For detailed implementation and code, refer to the Jupyter notebook provided in this repository.

Feel free to explore and contribute to further enhancements of the project!
