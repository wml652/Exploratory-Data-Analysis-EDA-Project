##            Exploratory Data Analysis & Preprocessing Portfolio
This repository contains two data analysis projects focused on cleaning, transforming, and extracting actionable insights from raw business data. These notebooks serve as the foundational exploratory data analysis (EDA) and preprocessing steps required before deploying Machine Learning models.🛠️ Tech Stack & LibrariesLanguage: PythonData Manipulation: Pandas, NumPyData Visualization: Matplotlib, SeabornTime-Series: Datetime


##   📂 Project 1: 

Financial Risk & Loan Data AnalysisObjective: Clean raw loan data, handle outliers, and engineer financial features to evaluate credit default risk.Key Steps & Methodologies:Missing Value Handling: Identified and imputed missing income values using the median to maintain dataset integrity.   Outlier Treatment: Visualized loan amount distributions using boxplots and applied a capping strategy, clipping values to the 5th and 95th percentiles to remove extreme anomalies.   Feature Engineering:Calculated the Debt-to-Income (dti_ratio) using the cleaned loan amounts.   Segmented numerical credit scores into categorical variables (High Risk, Fair, Good, Excellent).   Bivariate Analysis: Analyzed historical default rates across the newly created risk categories to establish baseline predictive metrics.   Correlation Mapping: Generated a Seaborn heatmap to visualize the mathematical relationships between age, income, loan amount, and credit score.   


##            📂 Project 2: 


Retail Sales Performance & InsightsObjective: Transform raw transactional retail data into a structured format, analyze profitability, and generate an automated business dashboard.Key Steps & Methodologies:Data Cleansing & Type Conversion: Handled missing numerical values with median imputation, filled missing categorical regions with the mode, and converted date strings into workable Python datetime objects.   Time-Series Engineering: Extracted granular temporal features including Month, Quarter, DayOfWeek, and MonthName for seasonality analysis.   Performance Analytics:Aggregated total sales and profit margins by product category and region.   Calculated overall dataset profit margins (e.g., 25.36% overall margin).   Data Visualization Dashboard: Built a dynamic 2x2 Matplotlib dashboard featuring:   A dual-axis line chart for monthly sales and profit trends.A bar chart highlighting total sales by product category.A pie chart breaking down regional sales distribution.A trend line comparing average sales and profit by day of the week.Business Intelligence: Translated raw data into actionable recommendations, such as prioritizing the "Books" category (top performer), focusing promotions on Fridays, and re-evaluating low-performing regions.   

##  🚀 How to RunClone this repository to your local machine.  

Ensure you have the required libraries installed: pip install pandas numpy matplotlib seabornLaunch Jupyter Notebook or Jupyter Lab.Run the cells sequentially to view the data transformations and visualizations.
