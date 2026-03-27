🩺 Diabetes Prediction Data Analysis

📌 Overview

This project focuses on analyzing a diabetes prediction dataset to identify key risk factors associated with the disease. Diabetes is one of the most common chronic illnesses worldwide, and early detection is essential for effective management and prevention.

The dataset is obtained from Kaggle and includes various health and lifestyle attributes such as age, BMI, blood glucose level, gender, and smoking history. By performing data cleaning, exploratory data analysis (EDA), and visualization, this project aims to uncover patterns and trends that contribute to diabetes.

🎯 Objective

The main objectives of this analysis are:

 - Identify key risk factors contributing to diabetes
 - Analyze relationships between variables such as age, BMI, and blood glucose level
 - Understand the impact of lifestyle factors like smoking
 - Provide insights for early detection and prevention strategies
   
📊 Scope of Analysis

This analysis focuses on:

 - Relationship between:
   - Age
   - BMI
   - Blood Glucose Level
   - Smoking History
 - Distribution of diabetes cases based on:
   - Gender
   - Age groups

⚠️ Note: Some variables such as hypertension, heart disease, and HbA1c level are not included in the analysis scope.

👥 Target Audience
 - 👩‍⚕️ Healthcare professionals (early detection & patient monitoring)
 - 📊 Data scientists & researchers (predictive modeling)
 - 🏥 Public health organizations (awareness & prevention programs)
 - 👤 General public (understanding personal risk factors)
  
📂 Dataset Information

📌 Source

Dataset obtained from Kaggle:

https://www.kaggle.com/datasets/iammustafatz/diabetes-prediction-dataset

📊 Dataset Details
 - Total records: 100,000 patients
 - Format: CSV
 - Contains medical and lifestyle attributes
   
🔑 Selected Variables

Independent Variables:
 - Age
 - Gender
 - BMI
 - Smoking History
 - Blood Glucose Level

Dependent Variable:
 - Diabetes Status (0 = No, 1 = Yes)
   
🧹 Data Cleaning

Steps performed:

 - Replaced "No Info" in smoking_history with NA
 - Identified missing values using:
   - df_status()
   - complete.cases()
 - Removed missing values using:
   - na.omit()
 - Final cleaned dataset:
   -✅ 64,184 rows
   -❌ No missing values
  
 - Exported cleaned dataset:
  
    cleaned_data_diabetes.csv
   
📈 Data Analysis (EDA)

🔍 Univariate Analysis

1. Smoking History
 - Majority of patients: Never smoked
 - Significant number: Former smokers
 - Fewer current smokers
   
2. BMI Distribution
 - Most patients: BMI around 25
 - Majority range: 20 – 35
 - Higher BMI values are less common

3. Gender Distribution
 - Female: Highest count
 - Male: Second highest
 - Other: Very small proportion

🔗 Bivariate Analysis

1. Blood Glucose vs Diabetes
 - Diabetic patients have higher glucose levels
 - Greater variation in diabetic group
 - Some extreme outliers (>300)

2. Smoking History vs Diabetes
 - Most people (both groups): Never smoked
 - Higher diabetes presence in:
   - Former smokers
   - Current smokers
 - Suggests smoking may influence diabetes risk

3. Age vs Blood Glucose
 - Diabetic individuals:
   - Consistently higher glucose levels
 - Non-diabetic:
   - Stable glucose levels (<200)
 - Age does not significantly reduce glucose levels in diabetics
   

💻 Technologies Used
 - R Programming (RStudio)
 - Libraries:
   - tidyverse
   - ggplot2
   - funModeling
   - Hmisc
   - dplyr
     

⚙️ Key Processes

🧹 Data Cleaning
 - Handle missing values
 - Remove incomplete rows
 - Export cleaned dataset

📊 Visualization
 - Histogram (BMI distribution)
 - Bar charts (Smoking, Gender)
 - Boxplot (Glucose vs Diabetes)
 - Scatter plot (Age vs Glucose)

📌 Key Insights
 - Diabetes strongly linked to high blood glucose levels
 - Smoking history may increase diabetes risk
 - Most patients fall within normal to overweight BMI range
 - Gender distribution shows higher female participation in dataset
   

🚀 Conclusion

This analysis successfully identified important factors contributing to diabetes risk. Blood glucose level is the strongest indicator, while lifestyle factors such as smoking also play a role.

The findings can support:

 - Early diagnosis
 - Preventive healthcare strategies
 - Better awareness among individuals



💡 Future Improvements

 - Include machine learning model (prediction)
 - Use full dataset variables (HbA1c, hypertension, etc.)
 - Build dashboard (Power BI / Tableau)
 - Deploy web-based analytics system
   

👩‍💻 Author

Developed by Sofea Aleeya









