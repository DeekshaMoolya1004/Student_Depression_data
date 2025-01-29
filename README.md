Student Depression Analysis

Overview

This project aims to analyze and visualize the factors affecting student mental health, particularly depression, based on various attributes such as academic pressure, financial stress, work/study hours, sleep duration, and family history of mental illness. The dataset was created in MySQL using Workbench, cleaned, and then connected to Jupyter Notebook for data visualization.

Dataset Information

Dataset Name: student_depression

Source: Created and stored in MySQL Workbench

Data Cleaning: Handled missing values, removed inconsistencies, and ensured proper data types before analysis.

Columns:

id: Unique identifier for each student

Gender: Male/Female/Other

Age: Student's age

City: City of residence

Profession: Student or working professional

Academic Pressure: Level of academic stress

Work Pressure: Level of work-related stress

CGPA: Academic performance

Study Satisfaction: Satisfaction with study habits

Job Satisfaction: Satisfaction with work environment

Sleep Duration: Average sleep hours per day

Dietary Habits: Eating habits (healthy/unhealthy)

Degree: Educational qualification

Have you ever had suicidal thoughts?: Yes/No

Work/Study Hours: Average hours spent on work/study

Financial Stress: Level of financial burden

Family History of Mental Illness: Yes/No

Depression: Presence of depression symptoms

Technologies Used

Database: MySQL (Workbench for database creation and management)

Programming Language: Python

Libraries Used:

pandas - Data handling and preprocessing

matplotlib - Basic data visualization

seaborn - Advanced visualization with statistical insights

MySQL Connector - To establish a connection between MySQL and Jupyter Notebook

Visualization & Insights

Various types of charts were used to analyze trends:

Bar Charts - To analyze categorical variables like Have you ever had suicidal thoughts?

Line Charts - To examine trends in Sleep Duration over different categories

Pie Charts - To represent Financial Stress distribution

Correlation Analysis - To find relationships between Family History of Mental Illness and Depression

Box Plots & Histograms - To study the distribution of Work/Study Hours

Key Findings

Financial stress is a major factor in mental health issues.

Lack of sleep is directly linked to high depression levels.

Moderate work/study hours (6–8 hours) contribute to higher satisfaction levels.

Students with a family history of mental illness are more prone to depression.

Suicidal thoughts are significantly correlated with high work pressure, academic stress, and financial instability.

Future Scope

Implement predictive modeling to identify students at high risk of depression.

Expand dataset to include more psychological and behavioral factors.

Develop a dashboard for real-time mental health insights.

How to Use

Database Setup:

Import the dataset into MySQL Workbench.

Establish a connection between MySQL and Jupyter Notebook using mysql.connector.

Run Jupyter Notebook:

Execute Python scripts to load and clean data.

Perform visualizations using matplotlib and seaborn.

Analyze Results:

Explore trends and insights through generated charts.

Author

Diksha Diwakar Mulya(Computer Science Student | Data Analyst Enthusiast)
