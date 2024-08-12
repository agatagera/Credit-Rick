# Credit-Rick
## Project Overview
This project utilizes the Credit Risk Dataset sourced from Kaggle, specifically from the following link: [Credit Risk Dataset](https://www.kaggle.com/datasets/laotse/credit-risk-dataset
). The dataset provides a foundation for analyzing credit risk and building predictive models.
## Data Preprocessing
## 1. Data Upload and Initial Checks:

- Data is uploaded and loaded into a DataFrame.
- Checked for missing values and duplicates; removed them accordingly.
## 2. Filtering and Cleaning:

- Filtered out rows where person_age - 15 is less than or equal to person_emp_length.
- Removed entries where person_age exceeds 100 and entries with loan_percent_income or loan_int_rate equal to zero.
- Identified and handled outliers using Z-scores and domain knowledge (e.g., values in cb_person_cred_hist_length and loan_percent_income).
## 3. Exploratory Data Analysis (EDA):

- Generated summary statistics and visualizations, including boxplots and scatter plots.
- Analyzed correlations and distributions to understand relationships between features.
## 4. Feature Engineering:

- Applied one-hot encoding to categorical features.
- Analyzed correlations among features post-encoding.
## Model Building
### Data Preparation:

- Split the dataset into features (X) and target (y).
- Divided data into training and testing sets.
## Model Training and Evaluation:

- Logistic Regression: Trained and evaluated using confusion matrix and classification report.
- Decision Tree Classifier: Trained and evaluated.
- MLP Classifier: Trained and evaluated.
- K-Nearest Neighbors Classifier: Trained and evaluated.
## Key Findings
- Data cleaning was crucial for removing inconsistencies and outliers.
- Exploratory data analysis provided insights into data distribution and feature relationships.
- Multiple classifiers were evaluated to determine the best model for predicting loan status.

##Next Steps
Further model tuning and hyperparameter optimization.
Consider additional features or transformations to improve model performance.
