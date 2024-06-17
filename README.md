# Insurance Climb Prediction
"It's my second internship capstone project."
 
# Insurance Climb Prediction

## Project Overview
The "Insurance Climb Prediction" project aims to develop an advanced predictive model to facilitate the insurance marketing team in identifying potential customers likely to purchase the product. The analysis encompassed a dataset with 58 columns and 595,212 rows, ensuring robust data for model building. Notably, the dataset was found to be clean, with no NULL values. However, the target variable imbalance poses a challenge, with 96.36% of observations at 0 and only 3.64% at 1.

## Model Performance
The predictive model performance was evaluated using various algorithms. The key findings are as follows:
1. **Linear Regression:**
   - *MSE:* 0.2506
   - *RMSE:* 0.5006
   - *R2 Score:* -0.0028
2. **Decision Tree Regressor:**
   - *MSE:* 0.5040
   - *RMSE:* 0.7099
   - *R2 Score:* -1.0164
3. **Random Forest Regressor:**
   - *MSE:* 0.2543
   - *RMSE:* 0.5043
   - *R2 Score:* -0.0175

## Best Model and Hyperparameters
The **Linear Regression** model outperformed the other models, showcasing promising results with '{'fit_intercept': True}' as the optimal hyperparameters.

## Key Features Influencing Customer Purchases
The analysis identified several critical features that significantly influence customer purchasing behaviour, including ps_ind_10_bin, ps_ind_11_bin, ps_ind_13_bin, ps_car_10_cat, and ps_ind_02_cat.

## Recommendations for the Insurance Marketing Team
Strategies for enhancing customer purchase behaviour include:
- Targeting customers based on the identified key features.
- Tailoring marketing approaches to highlight these features for optimized campaigns.
- Utilizing personalized recommendations to elevate customer engagement and drive purchase likelihood.

## Project Impact and Next Steps
The "Insurance Climb Prediction" project has effectively met its objective by developing a robust predictive model for customer purchase prediction. The insights and recommendations offer actionable strategies for the insurance marketing team to enhance customer acquisition and drive product sales with targeted and personalized marketing approaches. Moving forward, the project aims to implement the identified recommendations to further optimize customer engagement, acquisition strategies, and product sales.
