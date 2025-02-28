# Diabetes Prediction Model

## Key Steps Followed in the Project:

### 1. Data Loading and Exploration:
- The dataset was loaded and explored using methods like `df.info()` and `df.describe()`, which helped in understanding the data types and basic statistics.

### 2. Preprocessing and Feature Selection:
- Divided the dataset into independent variables (`X`) and dependent variable (`y`).
- Split the data into training and testing sets (70-30 split).

### 3. Model Building:
- Built a logistic regression model and trained it using the `fit()` method.
- Evaluated the model using metrics like confusion matrix, accuracy score, and classification report.

### 4. Hyperparameter Tuning:
- Used `GridSearchCV` and `RandomizedSearchCV` to find the best hyperparameters (`C`, `penalty`, and `solver`).
- Applied these optimized hyperparameters to retrain the model, improving accuracy.

## Metrics:

- **Initial Model Accuracy:** 79.65%
- **After Hyperparameter Tuning (GridSearchCV):** 80.52%
- **After RandomizedSearchCV:** Accuracy is similar to GridSearchCV, with a slight improvement in precision.
