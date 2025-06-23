Task 1 - Data Cleaning & Preprocessing

About this Task:
Hey! This is my first task where I learned how to clean and preprocess data properly before using it in Machine Learning models.

I used the Titanic dataset for this task.

What I did in this task:

1.Imported the Titanic dataset using Pandas.

2.Explored the data — like checking data types, missing values, etc.

3.Handled missing values — filled ‘Age’ with median and ‘Embarked’ with mode.

4.Removed the 'Cabin' column because it had too many missing values.

5.Converted categorical data to numbers — like changing 'Sex' to 0 & 1, and One-Hot encoding 'Embarked'.

6.Normalized the 'Age' and 'Fare' columns using StandardScaler.

7.Found outliers using boxplots and removed Fare outliers using IQR method.

8.Finally checked the cleaned data and saved it as a new CSV file.

Titanic-Dataset.csv — the original dataset I used.
