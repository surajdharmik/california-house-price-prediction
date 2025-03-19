# california-house-price-prediction

Overview

This project aims to predict housing prices using machine learning techniques. By leveraging data on various property attributes such as location, size, and amenities, we build predictive models to estimate housing prices accurately. The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model training, and evaluation.

Features

Data preprocessing (handling missing values, outlier removal, feature encoding)

Exploratory Data Analysis (EDA) with visualization

Feature engineering to enhance model performance

Comparison of multiple machine learning models (Linear Regression, Random Forest, XGBoost)

Performance evaluation using metrics like RMSE, MAE, and R² Score

Technologies Used

Programming Language: Python

Libraries: Pandas, NumPy, Scikit-learn, XGBoost, Matplotlib, Seaborn

Machine Learning Techniques: Regression models, ensemble learning, feature selection

Visualization Tools: Seaborn, Matplotlib, Plotly

Installation

Prerequisites

Make sure you have Python installed. You can set up a virtual environment to manage dependencies.

python -m venv venv
source venv/bin/activate  # On Windows use 'venv\Scripts\activate'

Install Dependencies

Run the following command to install the required packages:

pip install -r requirements.txt

Dataset

The dataset used contains details on:

Location (city, neighborhood, coordinates)

Structural features (bedrooms, bathrooms, square footage)

Economic indicators (market trends, interest rates)

Additional features (pools, garages, gardens)

Usage

Running the Project

Clone the repository:

git clone https://github.com/your-username/housing-price-prediction.git
cd housing-price-prediction

Run the script:

python train_model.py

Evaluate model performance:

python evaluate.py

Model Performance

The models were evaluated using:

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

Results
