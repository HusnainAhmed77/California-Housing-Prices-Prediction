This project applies machine learning regression models to predict median house prices in California districts based on census data. The dataset comes from Kaggle’s California Housing dataset, which contains features such as median income, average rooms, population, and geographical location.

📌 Objectives
Explore and clean the housing dataset
Perform feature preprocessing (handling NaN values, encoding, scaling)
Train and compare multiple regression models
Evaluate performance using MSE (Mean Squared Error) and R² score
Identify the best model for housing price prediction

🛠️ Tech Stack
Python
Pandas, NumPy – Data preprocessing
Matplotlib, Seaborn – Visualization
Scikit-learn – Machine learning models

📊 Models & Results
Model	MSE	R² Score
Linear Regression	5,062,019,613.46	0.6137
Decision Tree	4,693,791,963.22	0.6418
Random Forest	2,523,161,074.32	0.8075
Gradient Boosting	3,164,717,454.36	0.7585
Support Vector Regressor	13,741,706,794.29	-0.0487

✅ Best Model: Random Forest Regressor with R² = 0.8075
