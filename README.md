# Customer Churn Prediction System

## Overview

Machine Learning system that predicts which customers are likely to leave, enabling proactive retention strategies and significant cost savings.

## Business Impact

ROI: 621.3% - Every $1 invested returns $6.21
Annual Profit: $185,150
Churn Detection Rate: 79% - Catches 4 out of 5 customers who will leave
Revenue Saved: $247,800 annually

## Model Performance

Algorithm: Logistic Regression with Feature Selection
ROC-AUC Score: 0.832 (Excellent performance)
Recall: 79% (High churn detection rate)
Precision: 49% (Balanced approach)
Dataset Size: 7,043 real telecommunications customers

## Technologies Used

Core Technologies:
- Python 3.8+
- pandas 2.0.3
- scikit-learn 1.3.0
- numpy 1.24.3

Visualization & Analysis:
- matplotlib 3.7.1
- seaborn 0.12.2
- Jupyter Notebook

Machine Learning Techniques:
- Classification algorithms
- Feature engineering and selection
- Cross-validation
- Model optimization

## Dataset Features

Customer Demographics:
- Age, gender, partner status
- Dependents and family structure
- Geographic information

Service Usage Patterns:
- Tenure (months with company)
- Monthly charges
- Total charges paid
- Service utilization metrics

Contract Details:
- Contract type (monthly, yearly, two-year)
- Payment method
- Billing preferences
- Auto-payment status

Service Subscriptions:
- Internet service type
- Phone service options
- Streaming services
- Security and backup services

## Key Business Insights

1. Financial Predictors: Total charges and monthly charges are the strongest churn indicators
2. Customer Lifecycle: New customers with low tenure represent the highest churn risk
3. Contract Structure: Month-to-month contracts show 3x higher churn rates than long-term contracts
4. Service Type Impact: Fiber optic customers demonstrate higher churn rates compared to DSL users

## Project Structure

Customer_Churn_Prediction/
├── Customer_Churn_Prediction_Project.ipynb    # Main analysis notebook
├── README.md                                  # Project documentation
├── requirements.txt                           # Python dependencies
└── data/
    └── dataset_info.md                       # Dataset documentation

## Installation and Usage

Prerequisites:
- Python 3.8 or higher
- Jupyter Notebook or JupyterLab

Setup Instructions:

1. Clone the repository
   git clone https://github.com/yourusername/Customer_Churn_Prediction_Project.git
   cd Customer_Churn_Prediction_Project

2. Install required packages
   pip install -r requirements.txt

3. Launch Jupyter Notebook
   jupyter notebook

4. Open and run Customer_Churn_Prediction_Project.ipynb

## Model Development Process

Data Preprocessing:
- Handled missing values in TotalCharges column
- Encoded categorical variables using LabelEncoder
- Applied StandardScaler for feature normalization
- Performed train-test split with stratification

Feature Engineering:
- Correlation analysis to identify key predictors
- Feature importance ranking using Random Forest
- Selection of top 8 most impactful features
- Removal of low-impact variables

Model Selection:
- Evaluated Logistic Regression, Random Forest, and SVM
- Optimized for business metrics rather than accuracy alone
- Applied class balancing to address churn imbalance
- Cross-validated performance metrics

## Business Applications

Telecommunications Industry:
- Reduce customer acquisition costs
- Optimize retention campaign targeting
- Improve customer lifetime value

SaaS and Subscription Services:
- Identify at-risk subscribers
- Implement proactive retention strategies
- Reduce revenue churn

Financial Services:
- Prevent account closures
- Enhance customer relationship management
- Optimize retention investment allocation

## Future Enhancements

Technical Improvements:
- Implementation of real-time prediction API
- Integration of deep learning models for improved accuracy
- Development of ensemble methods for robust predictions

Business Intelligence:
- A/B testing framework for retention campaigns
- Customer segmentation for personalized strategies
- Advanced feature engineering from customer behavior data

Operational Integration:
- Automated alert system for high-risk customers
- Dashboard for real-time churn monitoring
- Integration with CRM systems

## Performance Metrics

Model Performance Comparison:
- Logistic Regression: Accuracy 73.0%, Precision 49%, Recall 79%, F1-Score 61%, ROC-AUC 0.832
- Random Forest: Accuracy 79.5%, Precision 64%, Recall 51%, F1-Score 57%, ROC-AUC 0.825
- SVM: Accuracy 79.3%, Precision 65%, Recall 48%, F1-Score 55%, ROC-AUC 0.791

## Author

Tzipora Elbaz
Machine Learning Engineer
Specializing in predictive analytics and business intelligence

## Contact

For questions or collaboration opportunities, please reach out through GitHub issues.

Note: This project demonstrates end-to-end machine learning pipeline development with focus on business impact and ROI optimization.
