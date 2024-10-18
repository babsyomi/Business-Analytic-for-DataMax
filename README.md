# Customer Churn Analysis

## Project Overview

This project aims to analyze customer churn data to understand the factors that influence customer retention and churn. The analysis involves several steps, including data preprocessing, exploratory data analysis, feature engineering, and building a predictive model using logistic regression.

## Steps Involved

1. **Importing Required Libraries**: Import necessary libraries for data manipulation, visualization, and model building.
2. **Creating a Sample Dataset**: Generate a synthetic dataset representing customer information and churn status.
3. **Data Preprocessing and Cleaning**: Handle missing values, remove duplicates, and create new features.
4. **Feature Engineering and Data Transformation**: Scale numeric features and create additional features for better model performance.
5. **Data Quality Assessment**: Assess the balance of the target variable and visualize feature relationships.
6. **Exploratory Data Analysis**: Visualize data distributions and relationships between features and the target variable.
7. **Model Building - Logistic Regression**: Split the data into training and test sets, build a logistic regression model, and evaluate its performance.
8. **Saving Results**: Save the cleaned dataset and visualizations to the `data` folder.

## Key Interpretation and Conclusion

- **Data Balance**: The dataset is checked for balance in the target variable (churn). This ensures that the model is not biased towards any class.
- **Correlation Analysis**: A correlation heatmap is generated to understand the relationships between different features. This helps in identifying important features for the model.
- **Age Distribution**: The age distribution of customers is visualized to understand the demographic spread.
- **Monthly Spend vs Churn**: The relationship between monthly spend and churn is analyzed using a box plot. This helps in understanding if spending patterns influence churn.

## Results

- **Best Model Parameters**: The logistic regression model is tuned using GridSearchCV to find the best parameters.
- **Model Accuracy**: The accuracy of the model is evaluated on the test set, and a classification report is generated to provide detailed performance metrics.

## Files

- `data/customer_data.csv`: Original synthetic dataset.
- `data/cleaned_customer_data.csv`: Cleaned dataset after preprocessing.
- `data/correlation_heatmap.png`: Correlation heatmap of features.
- `data/age_distribution.png`: Age distribution plot.
- `data/monthly_spend_vs_churn.png`: Box plot of monthly spend vs churn.

## Conclusion

The analysis provides insights into the factors affecting customer churn. The logistic regression model, with its tuned parameters, offers a reliable way to predict customer churn based on the available features. The visualizations and cleaned dataset provide a comprehensive understanding of the data and its characteristics.