🇳🇬 Analysis of State Education Budgets vs. Exam Performance

📌 Project Overview
This project investigates the correlation between State Education Budget Allocations (%) and National Exam Performance (WAEC Pass Rates) across Nigeria. As a novice data scientist, I aimed to see if higher financial investment by state governments directly translates to better academic outcomes for students.

🧪 The Hypothesis
"Regional Dominance": I hypothesised that geographical and historical factors (Geopolitical Zones) might influence exam success more strongly than individual state budget percentages.

🛠️ The Data Stack
Python: Core programming language.

Pandas: Used for data cleaning, merging NBS exam data with BudgIT budget data, and mapping states to Geopolitical Zones.

Matplotlib & Seaborn: Used to create visualisations (Bar Charts and Scatter Plots) to identify trends.

Data Sources:

National Bureau of Statistics (NBS) for 2024 Exam Results.

BudgIT Nigeria for 2023 State Budget Implementation.

📈 Key Findings
The Regional Cluster: There is a clear performance divide across Geopolitical Zones.
The Spending Paradox: Interestingly, the analysis showed a slight negative correlation between budget percentage and pass rates. This suggests that the volume of money allocated is less important than the efficiency with which those funds are utilised.

The South East Outlier: The South East zone showed the highest average pass rates, even in states where the education budget percentage was not the highest in the country.

Weak Linear Correlation: The scatter plot revealed that a high budget percentage does not automatically guarantee a high pass rate, suggesting that spending efficiency and historical literacy are critical factors.

📂 Repository Structure
notebooks/: Contains the Jupyter Notebook (.ipynb) with the full Python code.

data/: Placeholder for the datasets used (following NBS and BudgIT standards).
