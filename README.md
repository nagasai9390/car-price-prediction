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
Histogram of Car Prices
<img width="990" height="590" alt="image" src="https://github.com/user-attachments/assets/eac18096-fa49-4cb5-b66f-609959f84d1d" />

<img width="1389" height="590" alt="image" src="https://github.com/user-attachments/assets/c49b882b-1d3a-48e5-956c-06da9ab81b39" />

<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/aa6d9333-7cf3-42e6-9f5f-a39b1e20f04e" />

<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/b25cc60d-7b23-41b0-9165-887e2759845c" />

<img width="989" height="590" alt="image" src="https://github.com/user-attachments/assets/b03c52ec-28c9-4bf2-a5c5-f5ef9eb7d2c8" />

<img width="790" height="490" alt="image" src="https://github.com/user-attachments/assets/54746486-95a2-49f0-bcc4-afc5e43a7424" />

<img width="1390" height="590" alt="image" src="https://github.com/user-attachments/assets/85236e4e-962f-41c3-93f4-4d46ab3f37f6" />


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


