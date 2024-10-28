# Salaries_csv_EDA
The dataset is derived from Kaggle Dataset: 
The dataset contains information about employee salaries, with columns such as:

Id: Identifier for each employee.

EmployeeName: Employee’s name.

JobTitle: Position held by the employee.

BasePay, OvertimePay, OtherPay, Benefits, TotalPay, and TotalPayBenefits: Various compensation fields.

Year: The year of the record.

Agency: Agency associated with the employee, in this case, consistently "San Francisco."

Here’s a summary of key findings in the data:

Missing Data: The BasePay column has 605 missing entries, while Benefits has 36,159 missing values, and Status has a high number of missing entries (110,535). Additionally, Notes is entirely empty.

Categorical Data:
JobTitle has 2,159 unique roles, with "Transit Operator" being the most common position (7036 occurrences).

The Agency column is consistent with a single value, "San Francisco," and can likely be ignored for analysis.
Numerical Data:
TotalPay and TotalPayBenefits show high variance, with some negative values, possibly indicating errors or adjustments.
The data spans 2011 to 2014, allowing for multi-year analysis.

Here are the initial visualizations and insights:

Distribution of Total Pay: The distribution shows a positive skew, indicating most employees earn lower total pay, with a smaller number of employees in higher pay brackets.

Average Total Pay by Year: This shows a slight increase in average total pay over time, suggesting potential adjustments in salaries, bonuses, or other pay elements.

Top 10 Job Titles by Average Total Pay: High-paying roles include executive and senior managerial positions, as expected, with significant pay differences across these top positions.
