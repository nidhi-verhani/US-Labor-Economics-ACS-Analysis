📊 ACS Income and Labor Analysis (2021–2023)
🎓 Author: Nidhi Verhani
Master of Business Analytics, University of California, Riverside

🧾 Overview
This project analyzes U.S. Census American Community Survey (ACS) data (2021–2023) to understand how demographic and socioeconomic variables influence income and labor force participation.
Using R, the analysis applies statistical and machine learning models to uncover key relationships across education, gender, hours worked, and state-level factors.

⚙️ Methods and Tools
Language: R (R Markdown, RStudio)
Libraries: tidyverse, caret, rpart, ggplot2, dplyr, readr
Data: ipums_final_cleaned_2021_2023.csv (ACS microdata from IPUMS)
Files:
Final_project_286B.Rmd – main R Markdown source code
Final_project_286B.html – knitted HTML report
ipums_final_cleaned_2021_2023.csv – dataset
README.md – documentation
📈 Key Findings
Education and hours worked were the strongest predictors of income.
Gender gap: Males earned ~23% higher median income on average.
State variation: Income varied significantly by state, reflecting local labor conditions.
Regression model: Achieved R² = 0.81, explaining 81% of income variation.
Decision tree model: Provided interpretable splits on education level and work hours, highlighting clear thresholds for higher income groups.
🧩 Steps in the Analysis
Data Cleaning – handled missing values, recoded categorical variables.
EDA – visualized income distribution by gender, education, and state.
Modeling – ran multiple regression and decision tree models.
Model Evaluation – compared RMSE, R², and interpretability.
Conclusion – summarized insights and implications for policy and workforce planning.
