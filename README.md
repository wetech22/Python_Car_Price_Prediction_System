# Python_Car_Price_Prediction_System
# Car Price Prediction System
A machine learning project that predicts the price of used cars based on features such as model name, company, fuel type, manufacturing year, and kilometers driven. This beginner-friendly project demonstrates the use of regression modeling and preprocessing techniques in a real-world dataset.

# Dataset Overview
Source: Kaggle  
File Used: quikr_car.csv  
Features: name , company , year , Price , kms_driven , fuel_type

# Technologies & Libraries Used
Language: Python  
Libraries:
pandas, numpy, matplotlib
scikit-learn for ML modeling
OneHotEncoder, Pipeline, ColumnTransformer for preprocessing
train_test_split, LinearRegression, r2_score for training and evaluation

# ML Workflow
-Data Preprocessing:
Cleaned non-numeric price and kilometers fields,
Handled missing values,
Encoded categorical features: name, company, fuel_type.  
-Model Building:
Used LinearRegression inside a pipeline,
Applied OneHotEncoder to categorical columns via ColumnTransformer.  
-Training & Evaluation:
Trained using train_test_split (80/20 split),
Evaluated using R² Score,
Ran 1000 random splits to check for performance stability.  
-The model performs moderately and can be improved with more advanced techniques like feature engineering or non-linear models.


# Future Improvements
Use more advanced models like RandomForest or XGBoost  
Add GUI (e.g., Streamlit or Flask)  
Deploy the model online

