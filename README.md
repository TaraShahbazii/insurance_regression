# 🏠 Insurance Cost Prediction using Regression

🚀 **Predicting insurance costs using regression models and analyzing key factors affecting the costs.**

## 📌 About the Project
This project predicts insurance charges for individuals based on various factors such as:
- Age
- BMI (Body Mass Index)
- Number of children
- Smoking habits
- Region of residence

The goal is to build regression models that can accurately predict the insurance charges and analyze the influence of each feature on the costs.

## 🛠 Tools and Technologies
- **Python** 🐍
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, XGBoost

## 🎯 Steps in the Project
1. **Data Exploration:** Checked for missing values, outliers, and correlations.
2. **Feature Engineering:** Created dummy variables and normalized data.
3. **Model Implementation:** 
   - Linear Regression
   - Polynomial Regression
   - XGBoost Regressor
4. **Evaluation:** Used metrics like Mean Squared Error (MSE) and R² Score for performance evaluation.

## 📈 Results
- **Linear Regression:** MSE: 3387, R²: 0.76
- **Polynomial Regression (Degree=2):** MSE: 2861, R²: 0.81
- **XGBoost Regressor:** R² on test set: 0.81

## 📊 Visualizations
The project includes the following visualizations:
- **Correlation Heatmap:** To identify relationships between features.
- **Actual vs Predicted Prices:** To evaluate model performance.

## 📥 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/TaraShahbazii/insurance_regression.git
   cd insurance_regression
