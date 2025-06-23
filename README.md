# CatBoost Regressor for Insurance Charges Prediction

This project demonstrates how to use **CatBoost Regressor** to predict medical insurance charges based on demographic and lifestyle data. The dataset includes information such as age, sex, BMI, number of children, smoking status, and region.

## 🚀 Project Pipeline

The main steps in this machine learning pipeline are:

1. **Data Preprocessing**
   - Handled missing values (if any)
   - Converted categorical variables into numeric representations
   - Explored correlations and distribution of data

2. **Model Building & Training**
   - Used CatBoost Regressor for modeling
   - Tuned parameters using built-in CatBoost capabilities

3. **Model Evaluation**
   - Assessed performance using metrics like R² score and RMSE
   - Visualized prediction vs actual values

## 📁 Dataset

The dataset used is `insurance.csv`, which includes:
- `age`: Age of primary beneficiary
- `sex`: Gender
- `bmi`: Body mass index
- `children`: Number of children/dependents
- `smoker`: Smoking status
- `region`: Residential area in the US
- `charges`: Final insurance cost (target variable)

## 🧠 Model Used

- **CatBoost Regressor**: A gradient boosting algorithm that handles categorical features automatically and performs well on structured/tabular datasets.

## 📊 Evaluation Metrics

- R² Score
- K-Fold Cross Validation
- Adjusted R²

## 💻 Tools & Libraries

- Python
- Pandas
- Scikit-learn
- CatBoost

