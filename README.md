
# Objective : 
### The goal of this project was to develop a predictive model that accurately estimates age based on First Half Split time and Second Half Split Time. 
### The dataset used for this project was sourced from Kaggle and contained a comprehensive collection of home sales data. Link of the Dataset = "https://www.kaggle.com/datasets/runningwithrock/2024-boston-marathon-weather-and-splits"
# Data Preprocessing :
	1) Handling Missing Values: Imputed missing values using mean/mode for numerical/categorical features respectively.
	2) Feature Engineering: Created new features like Age of the house, Total Bathrooms, and others to capture more information.
	3) Encoding Categorical Variables: Applied one-hot encoding to convert categorical variables into numerical format.
	4) Scaling: Normalized numerical features to ensure they contribute equally to the model training.
# Exploratory Data Analysis (EDA) :
	1) Visualization: Used plots (histograms, scatter plots) to understand feature distributions and relationships with "Age".
	2) Correlation Analysis: Identified highly correlated features to target variable and among independent variables.
# Model Building :
## Multiple regression algorithms were tested to find the best model, including :
    1)Polynomial Regression    
    2)Support Vector Regression (SVR)
    3)Decision Tree  
    4)Random Forest   
    5)Gradient Boosting
		
# Model Evaluation :
### Cross-Validation : Used k-fold cross-validation to ensure the model's robustness and prevent overfitting.
# Results :
### The Support Vector Regression (SVR) provided the best performance with the lowest RMSE , MAE and MSE and highest R^2 score on the validation set, indicating its effectiveness in predicting Age.
# Conclusion : 
### The project successfully developed a machine learning model capable of predicting Age with high accuracy. 

# Technologies Used : 
	    1) Python
        2) Numpy and Pandas for data cleaning
        3) Matplotlib for data visualization
        4) Sklearn for model building
        5) Jupyter notebook
    

 

 
