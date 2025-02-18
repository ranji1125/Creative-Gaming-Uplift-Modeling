# Creative-Gaming-Uplift-Modeling

## Project Description
This project involved developing and implementing a targeted marketing campaign strategy using uplift modeling techniques. The aim was to maximize incremental profits by identifying the most responsive customer segments for marketing interventions. I utilized Logistic Regression, Random Forest, and XGBoost models to perform uplift modeling, comparing their efficacy and fine-tuning for optimal results.

## Technology Stack
- **Data Handling and Scripting**: Python, pandas, numpy
- **Machine Learning Libraries**: scikit-learn, XGBoost, pyrsm
- **Data Visualization**: matplotlib
- **Version Control and Collaboration**: Git, GitHub

## Key Accomplishments

### 1. Data Preparation and Management
- **Dataset Integration**: Integrated two distinct datasets from control and treatment groups for the marketing campaign.
- **Feature Engineering**: Developed essential variables and a combined dataset (cg_rct_stacked) for detailed uplift analysis.
- **Data Splitting**: Utilized stratified splitting to ensure balanced distribution of the target variable across datasets.

### 2. Model Development and Uplift Analysis
- **Logistic Regression Uplift Modeling**:
  - Trained separate models for control and treatment groups.
  - Calculated uplift by subtracting control predictions from treatment predictions and assessed model performance with uplift percentages and plots.
- **Random Forest Uplift Modeling**:
  - Fine-tuned a Random Forest model using hyperparameter optimization to enhance performance.
  - Evaluated the model's incremental profit potential compared to standard propensity models.
- **XGBoost Uplift Modeling**:
  - Implemented and fine-tuned an XGBoost model for uplift prediction.
  - Conducted a comparative analysis of uplift results against propensity models using both visual and quantitative methods.

### 3. Performance Evaluation and Optimization
- **Incremental Profit Calculation**: Estimated the total incremental profit achievable by targeting the top 30,000 customers as identified by each model.
- **Targeting Strategy Development**:
  - Determined the optimal customer targeting percentage to maximize profit based on model predictions.
  - Analyzed and compared various strategies to identify the most effective method using uplift and propensity models.
- **Model Comparison and Insights**:
  - Assessed the ability of each model to maximize incremental profit.
  - Found that XGBoost generally yielded the highest profit margins, outperforming both uplift and propensity models.

## Key Outcomes
- **Improved Targeting Precision**: Enhanced accuracy in identifying customers most likely to respond positively to the campaign, thus driving higher incremental profits.
- **Optimal Resource Allocation**: Informed strategic marketing resource allocation by pinpointing the exact percentage of the customer base to target.
- **Scalability and Adaptability**: Established methodologies that are scalable and adaptable for various campaigns or business scenarios, providing a solid foundation for future uplift modeling efforts.

## Summary
This project demonstrated the effective application of advanced machine learning techniques, particularly uplift modeling, in refining marketing campaign strategies. Through the use of Logistic Regression, Random Forest, and XGBoost, the project highlighted strategic customer targeting as a key to maximizing incremental profits, thereby making a significant contribution to data-driven marketing strategies.
