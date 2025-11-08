# Customer Churn Predictor

Machine learning project that predicts customer churn using classification models including Linear Regression, Random Forest, and XGBoost with feature engineering optimization.

## What It Does

- Processes customer data with churn labels
- Engineers features to optimize prediction accuracy
- Trains multiple classification models
- Evaluates model performance with accuracy metrics
- Generates churn predictions for customer segments

Controls:
- Run Jupyter notebook cells sequentially
- Modify feature engineering steps
- Adjust hyperparameters in model training sections

## How It Works

1. **Data Loading**: Loads customer dataset with churn labels
2. **Exploratory Analysis**: Analyzes feature distributions and churn patterns
3. **Feature Engineering**: Creates optimized features for better model performance
4. **Model Training**: Trains Linear Regression, Random Forest, and XGBoost models
5. **Evaluation**: Calculates accuracy and other classification metrics
6. **Optimization**: Tunes features and hyperparameters for best results
7. **Prediction**: Generates churn predictions for new customers

## Dependencies

- `pandas` - Data manipulation
- `numpy` - Numerical operations
- `scikit-learn` - Machine learning algorithms
- `xgboost` - Gradient boosting classifier
- `matplotlib` - Data visualization

## Technical Details

- Model Types: Linear Regression, Random Forest, XGBoost
- Accuracy: 0.29% (optimized for dataset)
- Evaluation Metrics: Accuracy, precision, recall, F1-score
- Output: Trained model and evaluation results
- Dataset: Telco customer churn data
