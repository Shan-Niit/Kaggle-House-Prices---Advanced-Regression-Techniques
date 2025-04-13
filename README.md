# Kaggle-House-Prices---Advanced-Regression-Techniques
House Prices - Advanced Regression Techniques

Project: House Price Prediction - Kaggle Competition
Objective:
The goal of this project was to predict house prices in Ames, Iowa, using machine learning techniques in the Kaggle competition "House Prices - Advanced Regression Techniques."

Approach:

Data Exploration and Preprocessing:

Analyzed and cleaned the dataset, handling missing values and ensuring the data was ready for modeling.

Numerical features were imputed with the mean value, while categorical features were imputed using the most frequent category.

Used OneHotEncoder to encode categorical variables and StandardScaler to scale numerical features.

Feature Engineering:

Examined potential feature relationships, and created new features to capture patterns in the data (such as dealing with outliers or adding polynomial features if necessary).

Applied feature scaling and transformation to improve model performance.

Pipeline Implementation:

Built a machine learning pipeline to streamline preprocessing and model training.

The pipeline consists of:

Imputing missing values (for both numerical and categorical data)

One-hot encoding for categorical variables

Scaling numerical variables with StandardScaler

This ensured reproducibility and efficiency in the workflow.

Model Selection and Evaluation:

Tried various models like Linear Regression, Random Forest Regressor, and Gradient Boosting to predict house prices.

Evaluated models using the Root Mean Squared Logarithmic Error (RMSLE) metric, which is the competition's evaluation metric.

Kaggle Submission:

Submitted predictions to Kaggle and received a score of 0.13686, indicating the model was performing reasonably well but could benefit from further refinement and tuning.

Results and Next Steps:

The model performed well for a first submission, landing around the top 50–60% of participants.

Future improvements include tuning hyperparameters, trying more complex models (e.g., XGBoost), and experimenting with additional feature engineering.

Technologies Used:

Python: for data manipulation, machine learning, and model evaluation

Pandas, Numpy: for data preprocessing and manipulation

Scikit-Learn: for model building, preprocessing, and evaluation

Kaggle: for competition participation and scoring
