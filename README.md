# Healthcare-Insurance-Analysis

Problem statement:

A significant public health concern is the rising cost of healthcare. Therefore, it's crucial 
to be able to predict future costs and gain a solid understanding of their causes. The 
insurance industry must also take this analysis seriously. This analysis may be used by 
healthcare insurance providers to make a variety of strategic and tactical decisions.

Objective:

The objective of this project is to predict patients’ healthcare costs and to identify factors 
contributing to this prediction. It will also be useful to learn the interdependencies of 
different factors and comprehend the significance of various tools at various stages of 
the healthcare cost prediction process.


Data Collection and Preparation:

Collected a dataset consisting of 10,000 patient records, including information on age, BMI, medical history, HbA1c levels, major surgeries, and hospitalization costs.
Preprocessed the data by performing data cleaning, handling missing values, and ensuring data consistency and integrity.

Exploratory Data Analysis:

Conducted exploratory data analysis to gain insights into the distribution and characteristics of the variables.
Examined the relationships between age, BMI, medical history, HbA1c levels, and hospitalization costs through visualizations and statistical analysis.
Noted that a significant portion of hospitalization costs fell within the range of $10,000 to $20,000.

Feature Engineering:

Utilized SQL queries to merge and analyze data from multiple tables, combining relevant variables for further analysis.
Calculated additional features such as the number of major surgeries and categorized variables as binary (e.g., presence or absence of heart issues, transplants, cancer history, smoking).

Hypothesis Testing:

Performed hypothesis testing, including t-tests and ANOVA, to assess the significance of various factors in driving healthcare expenditures.
Analyzed the p-values and confidence intervals to determine the impact of age, BMI, medical history, and HbA1c levels on hospitalization costs.

Predictive Modeling:

Developed a predictive model using advanced machine learning algorithms, including Stochastic Gradient Descent (SGD), Random Forest, and XGBoost.
Utilized the prepared dataset and applied regression techniques to estimate hospitalization costs.
Evaluated model performance using metrics such as Root Mean Squared Error (RMSE) and R-squared (R²), achieving robust results with RMSE values of 4469.65 for SGD, 3507.32 for Random Forest, and 3669.18 for XGBoost.

Visualization and Communication:

Created informative and visually appealing charts and graphs using Tableau to depict the relationship between hospitalization costs and variables such as age and BMI.
Highlighted the peak range of $10,000 to $20,000 in the hospitalization cost distribution, emphasizing the significance of this cost range.

Conclusion:

This project successfully analyzed hospitalization costs and identified key factors influencing cost variations. The findings provide valuable insights for healthcare insurance providers to optimize pricing strategies, allocate resources effectively, and improve patient outcomes. The predictive models and visualizations contribute to data-driven decision-making processes, ultimately leading to cost optimization and enhanced healthcare management.
