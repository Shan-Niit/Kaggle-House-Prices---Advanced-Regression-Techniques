# House Price Prediction on Kaggle

This project focuses on predicting house prices using the well-known **Ames Housing Dataset**. The approach involves data preprocessing, model training, and evaluation with an emphasis on using scikit-learn pipelines for a clean and reproducible workflow.

## Key Steps:

### 1. Data Preprocessing:
   - **Missing Data Imputation:**
     - Applied `SimpleImputer` to handle missing values.
     - Numerical features were imputed with the mean.
     - Categorical features were imputed with the most frequent value.
   - **Feature Scaling:**
     - Used `StandardScaler` to scale numerical features, ensuring that models that are sensitive to feature scaling perform better.
   - **Categorical Encoding:**
     - Utilized `OneHotEncoder` to handle categorical variables, converting them into a form that can be used by machine learning models.

### 2. Pipeline Construction:
   - **Numerical and Categorical Pipelines:**
     - Separated numerical and categorical data preprocessing into distinct pipelines.
     - Used `ColumnTransformer` to apply them to the dataset.
   - This helped ensure that the preprocessing steps were applied consistently to both training and test sets.

### 3. Model Training:
   - Trained a model using the preprocessed data. Although detailed model selection is not specified, the work focused on preparing the data for modeling with the correct transformations.

### 4. Evaluation:
   - **Kaggle Submission:** 
     - Submitting the predictions on Kaggle achieved a score of **0.13686**, placing me in the top **37.05%** of all participants.

## Observations:
- **Feature Engineering:** 
   - No additional feature engineering was done due to the large number of features already available in the dataset.
   - The focus was on improving the model's ability to work with the given features and preprocessing the data effectively.

## Results:
- **Kaggle Rank:** Top **37.05%** with a score of **0.13686** out of **4588** participants.
