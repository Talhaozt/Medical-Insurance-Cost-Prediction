# Medical Insurance Cost Prediction 🏥

This project focuses on predicting personal medical insurance costs using various Regression algorithms. The dataset includes patient features such as age, BMI, smoking status, and region.

##  Highlights
- **Exploratory Data Analysis (EDA):** Visualized correlations between features and insurance charges.
- **Data Preprocessing:** Implemented Label Encoding, One-Hot Encoding, and **StandardScaler** to ensure model stability.
- **Model Comparison:** Evaluated over 20+ models (Linear, Ridge, Lasso, ElasticNet, Gradient Boosting, etc.) using `LazyPredict`.

##  Performance Comparison
I compared multiple models to find the best fit for this specific non-linear dataset:

| Model | Adjusted R-Squared | R-Squared | RMSE |
| :--- | :--- | :--- | :--- |
| **GradientBoostingRegressor** | **0.90** | **0.90** | **3736** |
| RandomForestRegressor | 0.88 | 0.88 | 4056 |
| LinearRegression | 0.78 | 0.78 | 5537 |

##  Conclusion
While linear models provided a solid baseline (~78%), ensemble methods like **Gradient Boosting** significantly outperformed them by capturing non-linear relationships, achieving an impressive **90% accuracy**.

##  Tools Used
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-Learn
- LazyPredict
