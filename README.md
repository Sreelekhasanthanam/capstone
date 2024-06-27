### Project Title
Machine Learning Engineer Salary in 2024 - 2024 Machine Learning Engineer Salary Insights

**Author**
Sreelekha Santhanam

#### Executive summary
This dataset represents salary information for machine learning engineers in the year 2024. It includes details such as the level of experience, employment type, job title, salary amount, currency, employee residence, remote work ratio, company location, and company size. This information allows for analysis of salary trends, employment patterns, and other factors affecting machine learning engineer salaries in various locations and company settings.

#### Rationale
This information allows for analysis of salary trends, employment patterns, and other factors affecting machine learning engineer salaries in various locations and company settings.

#### Research Question

How do factors such as experience level, employment type, job title, location, remote work ratio, and company size impact the salaries of machine learning engineers in 2024?

#### Data Sources
The dataset represents salary information for machine learning engineers in 2024, which includes details such as level of experience, employment type, job title, salary amount, currency, employee residence, remote work ratio, company location, and company size.
https://www.kaggle.com/datasets/chopper53/machine-learning-engineer-salary-in-2024


#### Methodology
The strategy for solving this classification problem is the following

Feature Exploration (Initial analysis,Data cleansing, missing value detection, statistics, Data distribution, Data correlation)
Feature Visualization
Feature Engineering
Feature Importance
Base model
Cross-validation with 10 folds (Model Comparision)
Hyperparameter Tuning

#### Results
Analysis and modeling provide a comprehensive understanding of the salary data, highlighting key patterns, relationships, and predictive insights.
The Random Forest model's performance indicates its effectiveness in predicting salaries, with feature importance shedding light on the most influential factors.
Further steps could include refining the model, exploring additional features, and addressing any identified outliers or anomalies in the data.

#### Next steps
Exploring additional features.
Testing other machine learning models.
Addressing data limitations or improving data quality.
#### Outline of project
Salary Data Analysis and Predictive Modeling
1. Introduction
Objective: To analyze salary data, identify key patterns and relationships, and build a predictive model to forecast salaries based on various features.
Scope: Exploratory Data Analysis (EDA), outlier detection, advanced visualizations, and predictive modeling using machine learning techniques.
2. Data Overview
Dataset Description: Summary of the dataset, including the source, number of records, and features.
Initial Data Inspection:
Loading the dataset.
Displaying the first few rows of the dataset.
Checking for missing values.
Identifying data types of each column.
3. Exploratory Data Analysis (EDA)
Basic Statistics:
Summary statistics (mean, median, standard deviation, etc.).
Visualization of Salary Distribution:
Histogram and KDE plot of salary_in_usd.
Job Titles Analysis:
Count plot for the top 20 job titles.
Salary Distribution by Experience Level:
Boxplot and Violin plot by experience_level.
Salary Distribution by Employment Type:
Boxplot by employment_type.
4. Correlation Analysis
Correlation Matrix:
Calculating and visualizing the correlation matrix.
Identifying the correlation between salary_in_usd and other numeric features.
One-Hot Encoding:
Encoding categorical variables for correlation analysis.
5. Outlier Analysis
Outlier Detection:
Boxplot to visualize outliers in salary_in_usd.
Using the Interquartile Range (IQR) method to identify outliers.
Counting and analyzing the number of outliers detected.
6. Advanced Visualizations
Violin Plot of Salary by Experience Level:
Detailed visualization showing distribution shape and density.
7. Feature Importance Using Random Forest
Data Preparation:
One-Hot Encoding of relevant features.
Splitting data into training and testing sets.
Random Forest Model:
Training a Random Forest Regressor.
Calculating feature importances.
Visualizing feature importances.
8. Predictive Modeling: Random Forest
Model Training:
Training the Random Forest model on the training set.
Model Evaluation:
Predicting on the test set.
Evaluating model performance using Mean Absolute Error (MAE) and R-squared (R²) metrics.
9. Conclusion
Summary of Findings:
Key insights from EDA and correlation analysis.
Important features influencing salary predictions.
Model performance metrics.
Recommendations:
Suggestions for further analysis or model improvements.
Potential applications of the model.


##### Contact and Further Information
Sreelekha Santhanam -sreelekha.santhanam@gmail.com
