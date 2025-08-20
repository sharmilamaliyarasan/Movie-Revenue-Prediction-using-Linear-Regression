# 🎬 Movie-Revenue-Prediction-using-Linear-Regression

## 📋 Project Overview

This project predicts movie revenue based on marketing spend using linear regression.

The model identifies the relationship between investment in marketing and the expected revenue generated.

Intercept (Base Revenue): The minimum expected revenue even with no marketing.

Coefficient (Revenue per ₹1 Cr Marketing): The additional revenue expected for every ₹1 Cr spent on marketing.

## 🗂 Dataset Details

Feature Used (Input): Marketing_Spend_Cr

Target Variable (Output): Revenue_Cr

Other Columns (Not Used in this simple regression): Star_Power, Budget, Genre, Reviews etc.

Purpose: Estimate movie revenue for a given marketing spend.

## 📊 Visualization

Distribution of numeric variables:

<img width="981" height="739" alt="image" src="https://github.com/user-attachments/assets/8154f997-9271-4fab-bb1e-316497b6dbf9" />




The relationship between marketing spend and revenue is visualized below:

<img width="695" height="545" alt="image" src="https://github.com/user-attachments/assets/f34708e2-8e55-46d7-8ef6-caf302e12f33" />


 🔵 Red Dots → Actual movie revenue from dataset

## 📈 Regression Equation:

𝑅𝑒v𝑒𝑛𝑢𝑒 = 93.61 + 0.40 × 𝑀

Revenue=93.61+0.40×MarketingSpend

Example Prediction

👉 For a ₹10 Cr marketing spend, predicted revenue ≈ ₹97.65 Cr

## 🧠 Model Interpretation

⚡ Intercept (₹93.61 Cr): Base revenue expected even with zero marketing.

➕ Coefficient (₹0.40 Cr per 1 Cr marketing): Every ₹1 Cr spent on marketing adds ~₹0.40 Cr to revenue.

🔍 The weak slope suggests that marketing spend alone is not a strong driver of revenue. Other factors (Star Power, Genre, Reviews) matter more.

## 📉 Model Performance

R² Score: ~0.011 → Very low, meaning marketing spend explains very little variance in revenue.

RMSE: ~54.4 Cr → Average prediction error is around ₹54 Cr.

✅ Interpretation: Marketing spend alone is not a good predictor of movie revenue; need multiple regression with more features.

## 💡 Insights

🎬 Movie success cannot be explained by marketing spend alone.

🌟 Star Power, Genre, Audience Reviews, Budget play a major role.

📊 Using multiple regression with more features will improve prediction accuracy.

⚠️ Outliers may represent blockbuster hits or flops not aligned with marketing investment.

## ✅ Conclusion

Linear regression confirms a weak linear relationship between marketing spend and revenue.

Model accuracy is poor (low R², high RMSE).

Future improvement: Add multiple predictors (star power, reviews, genre, budget).

This project highlights the importance of multi-factor analysis for predicting box-office revenue.
