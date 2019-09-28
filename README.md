# polynomial_regression

# Data Wrangling

•	Cleaning the data which involves replacing null values with appropriate values such as mean and frequency

•	Standardization of data

•	Normalization

# Exploratory Data Analysis
•	First we check the type of data to determine what should be the right visualization tool for each data type

•	We can do: Correlation to see the effectiveness of features, regression plot to see the effectiveness of features on target variable but all of this on numerical data.

•	For categorical data: Boxplots and value count functions to determine the effectiveness.

•	Grouping is another way of analysis in which serval features are grouped together to see their effect on target variable also pivot is way to visualize this data easily

•	Heat maps can be used to see the effect of these groups on target

•	 Pearson correlation can be used to see the relation between features and target variable using P-values.

# Model Development
•	Finally, after getting everything ready we predict future values using the data we have through some model i.e. Linear Regression, multiple linear regression or Polynomial regression (there are many other models as well for different problems)

•	For Visualization i.e. what model should be used the Regression plots and Residual plots can be used but in the case of multiple linear regression when we have more than one features we can use Distribution Plots.

•	Pipeline is useful way to develop a model in which we give type of model, scale and type of regression as parameters.

•	Then after fitting the model we can compare the models using in-sample evaluation to determine which model is better for specific problem for that we can use R-Squared and Mean squared error Note: The smallest the MSE the better and the larger the R-Squared the better the model is.

# Model Evaluation and refinement
•	Import way to get the best results from any model is to split the data in Training and testing because if we don’t and present all the data to model for training it would be known to the model.

•	Again we can use R-Squared on training and testing data to check if the learning algorithm is suffering from Underfitting or Overfitting

•	Cross-validation-score is another method to find the error using specific number of folds.

•	We can visualize overfitting and underfitting using Distribution plots after fitting the model (Liner Regression and polynomial regression etc.) 

# Ridge regression and Grid Search
•	Ridge regression is an extension for linear regression. It’s basically a regularized linear regression model.

•	It penalizes the Theta so that model doesn’t get overfit.

•	There is regularization term Alpha in Ridge regression responsible for penalizing theta.

•	The term Alfa is a hyperparameter, sklearn has the class GridSearchCV to make the process of finding the best hyperparameter simpler and Automatic.
