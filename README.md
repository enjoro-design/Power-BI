# Diabetes-Dataset
https://www.kaggle.com/datasets/nanditapore/healthcare-diabetes?resource=download
GROUP 1
•Alex Metto
•Gideon Kiplangat
•Esther Njoroge
# User Manual: Diabetes patient health data from Kaggle

This user manual provides guidance on how to use and interpret the Power BI dashboard developed for analyzing diabetes-related health indicators. The dashboard uses an open-source Kaggle dataset containing key features like glucose, BMI, age, and diabetes outcomes.
Accessing the Dashboard
Open the Power BI report file (.pbix) using Power BI Desktop. Make sure you have the latest version installed. Navigate through the report pages using the tabs at the bottom of the Power BI window.

# Dashboard Visualization 
<img width="503" height="283" alt="image" src="https://github.com/user-attachments/assets/8f082054-d543-4d5a-9158-7365a7c5d1c0" />



# Dashboard Sections
Pie Chart - Diabetes Outcome Distribution
This chart shows the proportion of individuals diagnosed with diabetes (Outcome = 1) versus those not diagnosed (Outcome = 0). Use this visual to understand the prevalence of diabetes in the dataset.
Line Chart - Average Glucose vs Age
Displays how average glucose levels vary with age. Use this to identify trends, such as increased glucose levels among older age groups.
Bar Chart - Diabetes by Age Group
Compares the count of diabetic and non-diabetic individuals across predefined age groups. Helpful for identifying high-risk age brackets.
Scatter Plot - Glucose vs BMI
Plots glucose levels against BMI, with color coding for diabetes outcome. Useful for identifying clusters and relationships between these health indicators.

# Key Influencers Visual
This visual reveal which features (like age, BMI, glucose) most influence the diabetes outcome. Great for quick insights into what factors increase diabetes risk.
Decomposition Tree
Enables users to drill down into average glucose or BMI by other variables like age and outcome. Provides dynamic, step-by-step exploration.
Slicers
Use slicers to filter the dashboard by fields such as Age, Outcome, or BMI category. This helps narrow the analysis to specific subgroups.
KPI Cards
Shows summary statistics like Average Glucose, % Diabetic, and Average BMI. Useful for tracking key metrics at a glance.
Dashboard Interactivity
All visuals are interconnected. Selecting an item in one visual (e.g., an age group) will filter other visuals accordingly. Use this feature to explore relationships and patterns.

# Troubleshooting
If the dashboard visuals don't load correctly, click on 'Refresh' to reload the dataset. Make sure data source paths are correctly configured if using external sources.

# Key Findings
Demographic Analysis:
•
Age range: 21-81 years (average is 33)
•
Pregnancy count: 0-17 (average is 3.8)
•
BMI distribution: 18.2-67.1 (average ~32)
Diabetes Prevalence:
•
35% of patients have diabetes (952 out of 2768)
•
Prevalence increases with age and BMI
Risk Factor:
•
Strongest positive correlations with increase in glucose outcome:
o
Average skin thickness increases by 27.45
o
BMI increases by 25.31
o
Age increases by 24.14
o
Blood Pressure increases by 13.13

# Key Patterns:
1.
Glucose Threshold: Patients with glucose >140 mg/dL have 3x higher diabetes risk
Data Quality Issues:
•
Some missing values (coded as 0) in Blood Pressure, Skin Thickness, Insulin, and BMI
•
Potential outliers in Insulin measurements (some extremely high values)
