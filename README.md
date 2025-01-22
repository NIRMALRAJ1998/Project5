# Project5
**DS_Industrial Copper Modeling**

**Project Overview**
This project focuses on addressing challenges in the copper industry, specifically in sales pricing and lead classification, by applying machine learning techniques. The goal is to create models that predict sales prices and classify leads as successful (WON) or unsuccessful (LOST), ultimately helping businesses optimize pricing decisions and efficiently evaluate potential customers. The models deal with noisy, skewed data, applying methods such as data normalization, feature scaling, and outlier detection.

**Key Objectives**
Data Exploration and Preprocessing:
Explore the dataset to detect skewness, outliers, and inconsistencies.
Perform necessary data cleaning and transformation steps for better model accuracy.
Machine Learning Models:
Regression Model: Predict the continuous variable ‘Selling_Price’ using a regression model.
Classification Model: Classify leads as WON (Success) or LOST (Failure) using a classification algorithm.
Streamlit Application:
Develop a user-friendly interface to input values for sales data and receive predictions for ‘Selling_Price’ or lead status (WON/LOST).
Provide a smooth workflow where users can easily interact with the models and get instant predictions.

**Technologies Used**
Python: Programming language used for machine learning and data preprocessing.
Pandas & NumPy: Data manipulation and numerical computations.
Scikit-learn: Libraries for building and evaluating machine learning models.
Streamlit: Framework for building interactive web applications to deploy the models.
Matplotlib & Seaborn: Libraries for data visualization.
Jupyter Notebook: For data analysis, model building, and visualization.

**Model Overview**
Data Preprocessing:
Addressing skewness in continuous features.
Outlier detection and removal.
Data normalization and feature scaling.
Regression Model:
Predicts the continuous variable ‘Selling_Price’ using algorithms like Linear Regression, Random Forest Regressor, or Gradient Boosting.
Classification Model:
Classifies leads based on the ‘Status’ variable, predicting whether they will be WON or LOST using algorithms like Logistic Regression, Random Forest, or Support Vector Machine (SVM).
Streamlit Web Application:
Provides an easy-to-use platform for inputting data and receiving model predictions for sales price and lead status.

**How to Use**
Input Sales Data: Enter values for the relevant features like quantity, discount, etc., into the app.
Predict Sales Price: Get the predicted selling price for the entered data using the regression model.
Classify Leads: Enter details for the lead and get a classification for whether the lead will be WON or LOST.
Analyze: Visualize data distributions, skewness, and outliers through the app’s interactive charts.

**Conclusion**
This project leverages machine learning to address key challenges in the copper industry—optimizing sales pricing and classifying leads. With the help of regression and classification models, along with a convenient Streamlit interface, businesses can make more informed decisions and streamline their operations. The app offers real-time predictions and insights into the sales process, providing a comprehensive solution to pricing and lead classification problems.
