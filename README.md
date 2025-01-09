# House-Price-Prediction-Model

Overview:
The House Price Prediction Model is a machine learning project that uses housing data to predict the prices of houses based on features such as size, number of bedrooms, number of bathrooms, and location. The project demonstrates the use of data preprocessing, feature engineering, and regression techniques to build a predictive model.

Features:
Data preprocessing: Handling missing values, encoding categorical data, and feature scaling.
Model building: Implementing Linear Regression to predict house prices.
Model evaluation: Using Mean Squared Error (MSE) to evaluate the model's performance.
Visualization: Comparing actual vs. predicted prices using scatter plots.

Technologies Used
Programming Language: Python
Libraries:
pandas for data manipulation and preprocessing
numpy for numerical operations
scikit-learn for building and evaluating the machine learning model
matplotlib for data visualization

Dataset
The dataset contains information about houses, including features like:

Size: Area of the house in square feet.
Bedrooms: Number of bedrooms.
Bathrooms: Number of bathrooms.
Location: Categorical feature indicating the neighborhood.
Price: The target variable to predict.
The dataset is preprocessed to handle missing values, encode categorical variables, and scale numerical features for optimal model performance.

How It Works :-

Data Preprocessing:
Handled missing data.
Encoded categorical variables (e.g., location) using one-hot encoding.
Scaled numerical features for consistent input to the regression model.

Model Training:
Built a Linear Regression model using scikit-learn.
Split the dataset into training and testing sets to evaluate model performance.

Model Evaluation:
Calculated Mean Squared Error (MSE) to assess prediction accuracy.
Visualized Actual vs. Predicted Prices using scatter plots.
Results
Achieved a reasonable prediction accuracy (MSE: 1754318687330.6628). (Can be more accurate)
Scatter plot shows a strong correlation between actual and predicted prices, demonstrating the effectiveness of the model.

Working For Future Enhancements:
Explore other regression models such as Ridge, Lasso, or Random Forest for better predictions.
Perform hyperparameter tuning to improve the model's performance.
Use advanced visualization techniques for deeper insights.
Deploy the model as a web application using frameworks like Flask or Django.

Screenshots:

![image](https://github.com/user-attachments/assets/b4446b6f-1bdf-474e-b754-4f5a965f4690)


