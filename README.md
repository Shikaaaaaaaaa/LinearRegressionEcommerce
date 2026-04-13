# E-Commerce Customer Spending Analysis
## Predicting Yearly Amount Spent Using Linear Regression

## 🎯 Objective
Predict how much an e-commerce customer will spend yearly 
based on their behavior on the platform.

## 📊 Dataset
- 500 customers
- Features: Time on App, Time on Website, 
  Avg. Session Length, Length of Membership
- Target: Yearly Amount Spent

## 🔍 What I Did
- Exploratory Data Analysis with scatterplots and pairplot
- Trained a Linear Regression model
- Evaluated using MAE, MSE, RMSE and R²
- Analyzed residuals and Q-Q plot to validate model assumptions

## 💡 Key Insights
- Length of Membership is the strongest predictor (coeff: +61.30)
- Time on App has strong impact (coeff: +38.81)
- Time on Website has almost zero impact (coeff: +0.28)
- Business recommendation: invest in retention and app 
  experience over website development

## 🛠️ Tools Used
Python, Pandas, NumPy, Scikit-learn, Seaborn, Matplotlib, SciPy

## 📁 Files
- `Linear_Regression_E_commerce.ipynb` — full analysis notebook
- `Ecommerce_Customers.csv` — dataset
