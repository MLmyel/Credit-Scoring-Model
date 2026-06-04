# Credit Scoring Predictive Model
This project develops a predictive credit scoring model to help a consumer credit company mitigate rising default rates. By analyzing a robust client dataset, the project structured the data for modeling to enhance and automate credit concession decisions. Additionally, it features a practical simulator designed for account managers to apply the model's insights in real-world scenarios.  

   
## 🤖 Technologies
* Python
* pandas
* NumPy
* scikit-learn
* Statsmodels
* Matplotlib
* Seaborn
* SciPy

   
## 💻 Process
* Loaded and inspected the client dataset, confirming data integrity with no missing values.
* Transformed categorical variables using One-Hot Encoding for nominal data, intentionally dropping the first category to prevent multicollinearity.
* Applied Ordinal Encoding for education levels to preserve their inherent hierarchical structure within the dataset.
* Dropped non-predictive identifier columns to optimize the information for algorithm training.
* Conducted Exploratory Data Analysis (EDA) to evaluate statistical metrics and visualize the distribution of features and the target variable.

   
## 🎯 Findings
* Successfully engineered a structured dataset, transforming the initial variables into machine-learning-ready features without data loss.
* The Exploratory Data Analysis provided a clear baseline understanding of the client portfolio's credit score distribution and demographic patterns.
* The analytical framework establishes a data-driven foundation to evaluate client risk, directly addressing the business challenge of default rates.
* The integration of the Excel-based simulator bridges the gap between data science and business operations, creating an actionable tool for precise credit approvals.
