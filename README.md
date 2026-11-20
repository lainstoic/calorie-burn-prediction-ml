# Calorie Burn Prediction Using Machine Learning

Developed and evaluated machine learning regression models to predict calories burned during physical exercise using biometric and workout-related data.

The project compares **Ridge Regression, Random Forest, XGBoost, and Multi-Layer Perceptron (MLP)** across multiple preprocessing strategies.

### Key Features
- Analyzed two fitness datasets containing 15,000 and 973 records.
- Engineered features including BMI, heart rate interactions, and workout duration.
- Applied Recursive Feature Elimination (RFE) for feature selection.
- Optimized XGBoost hyperparameters using GridSearchCV.
- Evaluated model performance using RMSE and R².
- Used SHAP to interpret feature importance and model predictions.
- Analyzed prediction performance across different workout types.

### Results
- Tuned XGBoost achieved an R² of **0.9718** on the primary calorie dataset.
- Achieved an R² of **0.9534** on the gym-member dataset using a separately trained model.

### Technologies
Python · Pandas · NumPy · Scikit-learn · XGBoost · SHAP · Matplotlib · Seaborn · Jupyter Notebook
