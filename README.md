# car-price-prediction
 "Linear regression model to predict car prices with EDA, outlier treatment, and model evaluation"
🏎️ Car Price Prediction using Linear Regression
This project focuses on predicting car prices using a linear regression model. It involves a full data science pipeline — from data cleaning and exploratory analysis to model training, evaluation, and visualization.

📁 Dataset
The dataset contains detailed attributes of cars such as:

Brand

Engine specifications

Dimensions

Fuel type, aspiration, drive wheel, and more

Target: price (in USD)

✅ Project Workflow
1. Data Cleaning
Removed unnecessary columns: car_ID, CarName, etc.

Fixed typos in brand names (porcshce → porsche, toyouta → toyota, etc.)

Extracted car brands and encoded them numerically based on average price

2. Feature Engineering
Binary encoded fueltype and aspiration

One-hot encoded all other categorical features

Created a new column: CarBrandEncoded

3. Exploratory Data Analysis (EDA)
Visualized:

Price distribution

Brand-wise average price

Actual vs predicted prices

Identified high-priced outliers (Jaguar, BMW, Porsche, etc.)

4. Model Building
Built a Linear Regression model to predict car prices

Trained two versions:

✅ Original (with outliers)

✅ Cleaned (without outliers)

5. Evaluation
Model Version	R² Score	MAE	RMSE
Original (with outliers)	0.904	$1,909	$2,753
Cleaned (no outliers)	0.794	$1,447	$1,859

6. Residual Analysis
Visualized residuals with and without outliers

Found that removing outliers improved prediction consistency

📊 Visualizations
Boxplots of price distribution before and after cleaning

Actual vs Predicted plots with residuals

Brand-wise average car prices

🛠️ Tools Used
Python

Pandas, NumPy

Scikit-learn

Seaborn & Matplotlib

Jupyter Notebook

📁 Files Included
Cleaned_CarPrice_Assignment.csv

Cleaned_CarPrice_WithBrandEncoding.csv

Car_Price_Model.ipynb (full notebook)

Project visualizations


