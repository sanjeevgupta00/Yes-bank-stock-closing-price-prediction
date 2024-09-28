# Yes-bank-stock-closing-price-prediction


## Project Overview
This project analyzes the impact of the 2018 fraud case involving Rana Kapoor on Yes Bank's stock prices. We've developed predictive models to forecast monthly closing stock prices using historical data since the bank's inception.

## Dataset
The dataset includes monthly stock prices of Yes Bank, featuring:
- Opening price
- Closing price
- Highest price
- Lowest price

## Objectives
1. Analyze the relationship between the fraud case and stock price fluctuations
2. Develop and compare Linear Regression and Random Forest models for stock price prediction
3. Identify key factors influencing stock prices through feature importance analysis

## Methodology
1. Data Preprocessing:
   - Handled missing values
   - Feature engineering (created 'mean_ohl' feature)
   - Applied log transformation to handle data skewness

2. Exploratory Data Analysis:
   - Visualized stock price trends
   - Conducted hypothesis testing to compare pre-2018 and post-2018 stock prices

3. Model Development:
   - Implemented Linear Regression and Random Forest models
   - Performed hyperparameter tuning using RandomizedSearchCV

4. Model Evaluation:
   - Used metrics: RMSE, R2 score, Adjusted R2 score

## Key Findings
- The Random Forest model outperformed Linear Regression, achieving higher R2 scores
- Significant difference observed in stock prices before and after the 2018 fraud case
- Feature importance analysis revealed key factors affecting stock prices

## Tools Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Future Work
- Explore additional machine learning algorithms
- Incorporate external factors (e.g., market indices, economic indicators) into the model

## How to Use
1. Clone the repository
2. Run the file in Jupyter notebooks or Google Colaboratory

