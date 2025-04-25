# CreditPath-Simulating-Approval-Policies-and-Income-Stability-in-Rural-Loan-Decisions

# CreditPath: Simulating Approval Policies and Income Stability in Rural Loan Decisions

This project transforms the classic loan prediction problem into a strategic policy simulation framework. Instead of only classifying loan approvals, it evaluates how changes to approval criteria—such as relaxing credit history rules or prioritizing co-applicant income—can impact approval rates and risk. The goal is to support financial inclusion in rural and semiurban regions while maintaining responsible lending standards.

## Objective

- Build an interpretable machine learning model to predict loan approvals.
- Simulate real-world policy changes and evaluate their effect on approval outcomes.
- Provide actionable, data-driven recommendations for inclusive credit strategy design.

## Business Context

Many loan applicants in rural and semiurban areas are excluded due to rigid rules, like requiring formal credit history. This project explores how financial institutions can use machine learning and simulation tools to test policy changes before implementation, balancing inclusion with risk.

## Key Features

- **Data Cleaning and EDA**  
  Handled missing values with contextual logic and analyzed demographic trends related to loan approval.

- **Feature Engineering**  
  Created log-transformed income variables, household income aggregations, income tiers, and binary flags to better represent financial stability.

- **Model Training**  
  Trained and evaluated Logistic Regression, Random Forest, and XGBoost models using accuracy, ROC-AUC, confusion matrices, and F1-score.

- **Model Explainability**  
  Used feature importance and SHAP values to understand which features most influence the model’s decisions.

- **Policy Simulation Layer**  
  Simulated the business impact of three approval strategies, including relaxed credit history and prioritizing co-applicant income.

## Policy Simulations

1. **Relaxed Credit History for Income-Qualified Applicants**  
2. **Favor Applicants with Strong Co-applicant Income**  
3. **Allow Low-Income, No-Dependent Applicants from Rural/Semiurban Areas**


## Final Recommendations

- Credit history alone should not determine eligibility. Alternative scoring approaches may be needed.
- Applicants with strong co-applicant support should be prioritized even if their individual income is low.
- Rural, low-dependency, low-income applicants can be responsibly included through targeted approval pathways.
- The model can serve as a scoring and simulation tool, rather than a rigid classifier, to inform policy design.


