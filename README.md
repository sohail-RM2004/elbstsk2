# Titanic Survival Prediction — Data Analysis & Preprocessing

A comprehensive data preprocessing and exploration workflow applied to the Titanic dataset to prepare it for machine learning models.

---

##  Key Tasks Completed

### 1. **Data Loading & Exploration**
- Imported the Titanic dataset.
- Examined dataset structure, data types, and identified missing values.

### 2. **Missing Value Handling**
- Imputed missing **Age** values using **median**.
- Filled missing **Embarked** values with **mode**.
- Verified **Fare** for missing values and filled with **median** if needed.

### 3. **Feature Cleaning & Selection**
- Dropped non-informative or sparse columns: `PassengerId`, `Name`, `Ticket`, `Cabin`.
- Retained key features relevant for survival prediction.

### 4. **Categorical Encoding**
- Encoded `Sex` column using **label encoding** (`male`=0, `female`=1).
- Applied **one-hot encoding** to `Embarked`, creating `Embarked_C`, `Embarked_Q`, and `Embarked_S`.

### 5. **Feature Scaling**
- Standardized numerical features for uniform scaling.

### 6. **Outlier Detection & Removal**
- Used **boxplots** for `Age` and `Fare` to visualize outliers.
- Removed extreme outliers using the **IQR method**.

### 7. **Data Visualization & Insights**
- Created **histograms** for `Age` and `Fare` to study distributions.
- Used **correlation matrix** and **pairplots** to explore feature relationships.
- Identified key survival patterns:
  - Females had higher survival rates than males.
  - 1st class passengers survived more often.
  - Higher fares were linked to higher survival chances.
  - Children had better survival outcomes.

---

## Key Inferences
- **Gender**: Female passengers had higher survival rates.
- **Class**: 1st class passengers survived more frequently.
- **Fare**: Higher fare correlated with higher survival probability.
- **Age**: Children had an advantage in survival.


