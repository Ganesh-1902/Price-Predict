# Price-Predict

# House Price Prediction Project

This project implements a machine learning model to predict house prices using a dataset with features like location, size, age, and rooms. Developed as part of my YBI Gen AI Internship, it demonstrates data preprocessing, exploratory analysis, model training, and evaluation techniques.

# Features

- Data cleaning and outlier removal using domain knowledge and statistical methods.

- Exploratory Data Analysis (EDA) with visualizations like histograms, box plots, and correlation heatmaps.

- Multiple regression models including Linear Regression, Random Forest, and Gradient Boosting for price prediction.

- Model evaluation with metrics like RMSE, MAE, and R² scores.

# Dataset
Uses a standard house prices dataset (e.g., from Kaggle) with columns such as:

- Location coordinates (latitude, longitude)

- Housing median age

- Total rooms, bedrooms, population, households

- Median income and target house price (median_house_value)

- Preprocessing handles missing values, feature scaling, and encoding categorical variables.
​

# File Structure
text
project-root/
├── README.md              # This file
├── house_price_prediction.ipynb  # Main Jupyter notebook
├── data/                  # Dataset files (train.csv, test.csv)
├── models/                # Saved trained models (e.g., gbr.pkl)
├── submission.csv         # Predictions on test data
└── requirements.txt       # Dependencies

# Setup Instructions
Clone the repository: git clone https://github.com/yourusername/price-prediction.git

Install dependencies: pip install -r requirements.txt (includes pandas, scikit-learn, matplotlib, seaborn)

Run the notebook: Open house_price_prediction.ipynb in Jupyter and execute all cells.

# Example requirements.txt:

text
pandas
numpy
scikit-learn
matplotlib
seaborn
jupyter
Workflow
Load and explore data.

Clean data: Remove outliers, handle NaNs, feature engineering.

Train models and select the best via cross-validation.

Generate predictions and evaluate performance.
​

# Results
Achieved RMSE of X on test data with Gradient Boosting (update with your actual metrics). Visualizations show feature importance and prediction vs actual plots.

# Technologies Used

Python, Jupyter Notebook

Scikit-learn for ML models

Pandas, NumPy for data handling

Matplotlib, Seaborn for visualizations
​

#### YBI Gen AI Internship ####

This project fulfills the requirements for my YBI Foundation Generative AI Internship certificate. It showcases end-to-end ML pipeline skills for real-world regression tasks.

# Future Improvements

Deploy as a web app using Flask/Streamlit.

Hyperparameter tuning with GridSearchCV.

Ensemble more advanced models like XGBoost.

# Contributing
Fork, create a branch, make changes, and submit a pull request. Issues welcome!

