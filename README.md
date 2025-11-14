# 🧹 Task 1: Data Cleaning & Preprocessing – Titanic Dataset

## 🎯 Objective
Clean and prepare raw Titanic data for machine learning.

## 🧰 Tools Used
- Python
- Pandas, NumPy
- Seaborn, Matplotlib
- Scikit-learn

## 🔍 Steps Performed
1. Loaded dataset and explored basic information.
2. Handled missing values (median, mode, drop).
3. Encoded categorical variables using one-hot encoding.
4. Normalized numerical features using StandardScaler.
5. Visualized and removed outliers using boxplots and IQR.
6. Exported final cleaned dataset.

## 📈 Output
- Clean dataset: `titanic_cleaned.csv`
- Visualizations: Boxplots of Age & Fare
- Code file: `Task1_Data_Cleaning_Preprocessing.ipynb`




- # 🧹Task 2: Exploratory Data Analysis - Titanic Dataset
-        This project performs Exploratory Data Analysis (EDA) on the popular Titanic dataset, focusing on understanding passenger demographics, survival patterns, and feature distributions using Pandas, Matplotlib, and Seaborn.
-    
🎯 Objectives

1. Understand data structure and basic statistics
2. Handle missing values
3. Visualize each feature with histograms, boxplots, and countplots
4. Identify outliers and anomalies.
5. Explore relationships between features
6. Make basic conclusions from the visuals

📊 Key Visualizations

1️⃣ Histograms
     Used to analyze numeric columns:
          Age, Fare, Sibsp, Parch

2️⃣ Boxplots
    Used to detect outliers in numeric features

3️⃣ Countplots
      Used for categorical columns such as:
        Survived, Sex, Embarked, Passenger Class  (Pclass)

4️⃣ Correlation Matrix
       To study relationships between feature


🔍 Insights & Observations
 1. Survival Patterns
         Females survived more than males
         First-class passengers had the highest survival rate
         Children had a higher chance of survival compared to adults

2. Outliers
         Fare and SibSp columns contain significant outliers
         Boxplots were used to identify extreme values

3.  Family Influence
         Passengers traveling with small families (SibSp = 1 or Parch = 1) had slightly better survival outcomes

4. Pclass Effect
         Strong negative correlation between Pclass and Survival
         (Lower class number = higher chance of survival)


   🧑‍💻 Tech Stack

     Python
     Pandas
     Matplotlib
     Seaborn
     Jupyter Notebook


   📝 Conclusion

This EDA helps in understanding the Titanic dataset thoroughly and builds a strong foundation for machine learning model building. It provides insights into survival patterns and key numeric and categorical feature distributions.
