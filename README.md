# Titanic Survival Prediction Analysis

This project explores the famous **Titanic dataset** to analyze factors that influenced passenger survival rates and to build predictive models. It demonstrates skills in **data cleaning, exploratory data analysis (EDA), feature engineering, visualization, and machine learning modeling**.

## Project Overview
The Titanic dataset from [Kaggle](https://www.kaggle.com/c/titanic) provides demographic and travel information for passengers aboard the Titanic. The goal is to understand survival patterns and predict passenger survival using machine learning techniques.

### Key Steps:
1. **Data Cleaning**  
   - Handled missing values (Age, Cabin, Embarked).  
   - Converted categorical variables (Sex, Embarked, Pclass).  

2. **Exploratory Data Analysis (EDA)**  
   - Analyzed relationships between survival and features such as age, sex, class, and fare.  
   - Visualized distributions and correlations using plots.  

3. **Feature Engineering**  
   - Created new features such as family size and title extraction from passenger names.  
   - Normalized numerical features.  

4. **Modeling**  
   - Implemented classification algorithms (e.g., Logistic Regression).  
   - Evaluated the model with accuracy, precision, recall, and F1-score.  
   - Interpreted coefficients to understand the influence of features such as gender, class, and age on survival.  

5. **Results & Insights**  
   - Gender and class were the strongest predictors of survival.  
   - Feature engineering improved prediction performance.  
   - Achieved solid predictive accuracy on the test set.  

## Tech Stack
- Python (pandas, numpy, scikit-learn, matplotlib, seaborn)  
- Jupyter Notebook  
