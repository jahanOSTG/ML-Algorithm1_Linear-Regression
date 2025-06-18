#  Linear Regression on Custom Dataset

This repository demonstrates a full linear regression workflow using a dataset.

---

##  Dataset Overview

The dataset (`friend.csv`) contains the following columns:

| Column | Description                               |
|--------|-------------------------------------------|
| ID     | Unique identifier (ignored)               |
| size   | Custom feature (e.g., test score, item size, etc.) |
| Age    | Age of the individual                     |
| prize  | Prize or cost-related value               |
| Number | 🎯 Target variable                         |

---

## ✅ Steps Performed

### 1. Mount Google Drive  
To access the dataset stored in Google Drive.

### 2. Import Libraries  
Used libraries:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

### 3. Load and Preprocess Data  
- Removed unnecessary columns (`ID`, if not useful).  
- Handled whitespace in column names.  
- One-hot encoding skipped as no categorical columns exist.

### 4. Train-Test Split  
Split the data into training and testing sets using `train_test_split()`.

### 5. Train Model  
Trained a `LinearRegression()` model on the training data.

### 6. Prediction & Evaluation  
- Generated predictions on the test set.  
- Calculated **MAE**, **MSE**, **RMSE**, and **R²** for performance analysis.

### 7. Visualization  
-  **Regression Line Plot** to compare actual vs predicted values.  
-  **Residual Plot** to check errors.  
-  **Heatmap** to show correlation between all numeric features.

---
