# Credit Risk Modeling


## Project Overview:
In this project, we developed a robust predictive model to evaluate the credit risk of loan applicants. The goal was to accurately classify applicants into risk categories, thereby aiding financial institutions in making informed lending decisions.

## Key Techniques and Methodologies:

### 1. Data Collection and Preprocessing:
* Data Sources:The dataset was sourced from a financial institution’s loan records, including applicant demographics, financial history, and loan specifics.
* Data Cleaning: Addressed missing values, outliers, and normalization techniques.
### 2 Feature Selection:
* Statistical Tests: Utilized Chi-Square tests for categorical features and ANOVA tests for continuous features to evaluate the significance of each feature in relation to the target variable.
* Variance Inflation Factor (VIF): Analyzed multicollinearity among features, removing those with high VIF values to ensure model stability and interpretability.

### 3.Model Development:
* Algorithm Selection: Evaluated multiple algorithms, including logistic regression, decision trees, random forests, and gradient boosting machines, selecting the one that provided the best performance and interpretability balance.
* Training and Validation: Split the data into training (80%) and testing (20%) sets to build and validate the model. Performed cross-validation to fine-tune hyperparameters and prevent overfitting.

### 4. Model Evaluation:

Performance Metrics: Assessed model performance using accuracy, precision, recall, F1-score. The final model achieved an accuracy of 80% on the training data and 78% on the test data.

## Key Achievements:

* Improved Decision-Making: Enabled the financial institution to make more informed and data-driven lending decisions, reducing the risk of defaults.
* Model Performance: Achieved a high level of accuracy (80% on training data and 78% on test data), demonstrating the model’s ability to generalize well to unseen data.

## Tools and Technologies:

* Programming Languages: Python
* Libraries: pandas, numpy, scikit-learn, statsmodels
* Statistical Methods: Chi-Square test, ANOVA, VIF analysis
* Modeling Techniques:  DecisionTreesClassifier, RandomForestsClassifier, XGBoostClassifier


## Conclusion:
This project successfully combined advanced data science techniques with domain knowledge to create a practical and effective credit risk assessment model. By leveraging  rigorous feature selection processes, and robust model validation, we developed a tool that significantly enhances the financial institution's ability to manage credit risk.















