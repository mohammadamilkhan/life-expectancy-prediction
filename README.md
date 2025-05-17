# Life Expectancy Prediction using Machine Learning

This project analyzes global life expectancy data and applies regression models to predict life expectancy based on health, economic, and social indicators. By comparing models like Linear Regression, Random Forest, and XGBoost, we identify the most accurate predictors and modeling approaches.

---

## Problem Statement

Life expectancy is a crucial measure of a nation's health and development. Numerous factors such as GDP, healthcare investment, education, disease prevention, and nutrition contribute to life expectancy across countries. Despite rich historical health datasets, many countries struggle to use this data effectively for predictive insight. This project aims to build accurate models to predict life expectancy and help guide policy decisions using data-driven insights.

---

## Objective

- Analyze the relationships between socio-economic and health indicators and life expectancy.
- Build regression models to predict life expectancy using these features.
- Compare model performance to determine the most effective approach.
- Visualize actual vs predicted outcomes to evaluate model accuracy.
- Recommend data-driven strategies for improving global health forecasting.

---

## Insights

### Model Performance Ranking

- **Random Forest** performed best with the lowest RMSE (**1.65**) and highest R² score (**0.9686**).
- **XGBoost** followed closely with RMSE of **1.76** and R² of **0.9643**.
- **Linear Regression** had significantly lower performance (RMSE: **3.90**, R²: **0.8241**).

### Actual vs Predicted Correlation

- The **scatter plot** shows predicted values align tightly with actual life expectancy values.
- Strong correlation around the diagonal line confirms robust model behavior.

### Sample Prediction Comparison

- Bar charts for a sample of predictions show near-identical actual and predicted values.
- This validates consistency and low prediction error, especially with Random Forest.

---

## Conclusion

- **Tree-based models** (Random Forest, XGBoost) significantly outperform Linear Regression for life expectancy prediction.
- **Random Forest** is the best performer, offering **high accuracy and stability**.
- The models captured complex interactions between health, economic, and demographic indicators effectively.
- These predictive models can assist governments and organizations in shaping health policies and resource planning.

---

## Future Work

- **Feature Engineering**: Add more features like healthcare infrastructure, environmental quality, or lifestyle factors.
- **Data Expansion**: Include more recent years or country-specific datasets for higher granularity.
- **Model Tuning**: Use advanced hyperparameter optimization (e.g., Bayesian optimization).
- **Deployment**: Build an interactive dashboard or deploy via a web API for real-time predictions.
- **Fairness Analysis**: Explore potential biases in predictions across countries or income groups.

---

## Tools & Technologies

- Python, Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (Linear Regression, Random Forest)
- XGBoost
- Jupyter Notebook
