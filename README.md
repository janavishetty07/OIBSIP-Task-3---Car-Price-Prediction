🚗 Car Price Prediction 

This project is part of my Data Science internship and aims to predict the selling price of used cars based on various features such as the year of manufacture, fuel type, transmission type, kilometers driven, and more. The project uses a Linear Regression model built with Python and scikit-learn.

 Dataset
The dataset used contains features of used cars, including:

Year – Year of manufacture

Selling_Price – Price the car is being sold for

Present_Price – Price of the car when it was new

Kms_Driven – Total kilometers driven

Fuel_Type – Type of fuel used (Petrol, Diesel, CNG)

Seller_Type – Individual or Dealer

Transmission – Manual or Automatic

Owner – Number of previous owners

 Objective
To build a machine learning model that can accurately predict the selling price of a car based on input features. The project also includes data preprocessing, EDA (Exploratory Data Analysis), visualizations, and model evaluation.

🔧 Technologies Used
Python

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

📌 Project Workflow
Importing Libraries – Load all essential Python libraries.

Loading the Dataset – Load the CSV file using pandas.

Exploring the Data – Use .head(), .info(), .describe() to understand the dataset.

Visualization – Use Seaborn and Matplotlib to explore feature relationships and distributions.

Encoding Categorical Variables – Convert categorical features using pd.get_dummies().

Splitting Data – Divide the dataset into training and test sets.

Model Building – Train a Linear Regression model.

Prediction & Evaluation – Predict on test data and evaluate using MSE and R² score.

Visualization of Results – Plot actual vs predicted prices and residuals.

Insights – Explore how features like Fuel Type and Transmission impact the price.

📷 Visualizations
Pair plots to explore feature relationships

Box plots for price vs fuel type and transmission

Scatter plot of actual vs predicted prices

Residual plot to analyze prediction errors

✅ Conclusion
This project demonstrates how regression models can be applied to real-world datasets to generate valuable business insights. It highlights the importance of data cleaning, feature encoding, and visualization in building reliable ML models.

