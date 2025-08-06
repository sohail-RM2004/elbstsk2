<h1> Key Tasks Completed: </h1>

Data Loading & Exploration

Imported the Titanic dataset.

Explored dataset structure, data types, and identified missing values.

Missing Value Handling

Imputed missing Age values using median.

Filled missing Embarked values with mode.

Ensured Fare had no missing values (if present, filled with median).

Feature Cleaning & Selection

Dropped non-informative or sparse columns: PassengerId, Name, Ticket, Cabin.

Retained key features relevant for survival prediction.

Categorical Encoding

Encoded Sex column using label encoding (male=0, female=1).

Applied one-hot encoding to Embarked to create Embarked_C, Embarked_Q, Embarked_S.

Feature Scaling

Outlier Detection & Removal

Visualized Age and Fare using boxplots to detect outliers.

Removed outliers using the IQR method to improve data quality.

Data Visualization & Insights

Created histograms for Age and Fare to understand their distribution.

Used correlation matrix and pairplot to study feature relationships.

Identified key patterns and trends in survival rates based on class, gender, fare, and port of embarkation.

Key Inferences:
Females and 1st class passengers had higher survival rates.
Higher fares correlated with higher survival.
Most passengers were young adults, and children had better survival outcomes.

Outliers in Fare and Age were detected and handled properly
