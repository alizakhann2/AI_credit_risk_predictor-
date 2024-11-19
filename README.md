# Credit Risk Prediction Using AI-Driven Models

This project focuses on building AI-driven models for predicting credit risk in the microfinance sector. By leveraging advanced machine learning techniques and comprehensive feature engineering, the models deliver high accuracy and robust performance.

## Project Overview

Credit risk assessment is crucial for microfinance institutions to make informed lending decisions. This project applies machine learning algorithms to accurately distinguish between low- and high-risk borrowers, helping institutions minimize financial risk.

## Features

- **Advanced Algorithms**: Utilized Random Forest, Gradient Boosting, Logistic Regression, and Decision Tree models.
- **High Performance**: Achieved AUC values of:
  - Logistic Regression: 0.99
  - Decision Tree: 0.99
  - Gradient Boosting: 1.00
  - Random Forest: 1.00
- **Feature Engineering**: Created new financial ratios such as *income-to-age ratio* and *expenditure per dependent*, and generated polynomial features to enhance model accuracy.
- **Optimization**: Applied hyperparameter tuning using Random Search and Cross-Validation to achieve optimal model performance.
- **Stability Monitoring**: Implemented Population Stability Index (PSI) to track model stability over time.

## Implementation Details

1. **Data Preprocessing**:
   - Cleaned and transformed raw data, handling missing values and outliers.
   - Converted categorical variables into suitable formats for modeling.

2. **Feature Engineering**:
   - Generated new features based on feature importance rankings.
   - Created polynomial features to model non-linear relationships in the data.

3. **Model Development**:
   - Trained and tested four machine learning models.
   - Evaluated model performance using ROC AUC metrics to compare effectiveness.

4. **Hyperparameter Tuning**:
   - Used Random Search and Cross-Validation to fine-tune model parameters and maximize performance.

5. **Model Stability**:
   - Monitored prediction stability using the Population Stability Index (PSI) to ensure consistent performance across data shifts.

## Results

- **AUC Scores**: The models demonstrated exceptional performance, with AUC values of 0.99 for Logistic Regression and Decision Tree, and 1.00 for Gradient Boosting and Random Forest.
- **Reliability**: The use of PSI ensured that the models remained robust and reliable, even as data distributions evolved.

## Technologies Used

- **Programming Language**: Python
- **Libraries**: scikit-learn, pandas, numpy, matplotlib, seaborn

## Conclusion

This project showcases the potential of AI in transforming credit risk assessment for microfinance. By combining sophisticated algorithms, advanced feature engineering, and robust optimization techniques, the models offer significant improvements in predictive accuracy and reliability.

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/credit-risk-prediction.git

