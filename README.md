📊 Walmart Sales Data Analysis & Prediction
📌 Project Overview

This project focuses on analyzing Walmart sales data to uncover insights and build a machine learning model to predict future sales. It includes data cleaning, exploratory data analysis (EDA), visualization, and predictive modeling.

🎯 Objectives
Clean and preprocess raw sales data
Analyze sales trends across stores and time
Visualize patterns using charts
Build a model to predict weekly sales
📁 Dataset Information
Dataset: Walmart Sales Dataset (45 Stores)
Features include:
Store
Date
Weekly_Sales
Temperature
Fuel_Price
CPI
Unemployment
Holiday_Flag
🛠️ Technologies Used
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn
🔍 Data Cleaning Steps
Handled missing values (mean/mode)
Removed duplicate records
Converted date column to datetime format
Extracted Year, Month, Week
Renamed columns for consistency
📈 Exploratory Data Analysis (EDA)

Key insights:

Monthly and yearly sales trends identified
Top-performing stores analyzed
Holiday vs non-holiday sales compared
Correlation between features visualized
📊 Visualizations Included
Line chart (Monthly Sales Trend)
Bar chart (Sales by Store)
Pie chart (Holiday vs Non-Holiday Sales)
Scatter plots (Sales vs Temperature, Fuel Price)
Histogram (Sales Distribution)
Heatmap (Correlation matrix)
Box plot (Outlier detection)
🤖 Machine Learning Model
Model Used: Linear Regression & Random Forest
Features Used:
Store, Fuel Price, CPI, Unemployment, Month, Year
Evaluation Metrics:
Mean Absolute Error (MAE)
R² Score
📌 Results
Linear Regression provides baseline predictions
Random Forest improves accuracy
Key factors affecting sales identified
