
## 🚀 Workflow

1. **Data Collection & Exploration**
   - Load customer and transaction data
   - Initial EDA: missing values, outliers, trends

2. **Feature Engineering**
   - RFM features (Recency, Frequency, Monetary)
   - Tenure, average order value, etc.
   - Encoding categorical variables

3. **Model Development**
   - Baseline: Linear Regression
   - Advanced: Ridge, Lasso, Random Forest, XGBoost
   - Hyperparameter tuning with GridSearchCV

4. **Model Evaluation**
   - Performance metrics: RMSE, MAE, R² score
   - Cross-validation

5. **Visualization & Insights**
   - Feature importance
   - Predicted vs. actual plots
   - Business interpretation of results

## 📒 Notebooks

- [cltv_notebook.ipynb](notebooks/cltv_notebook.ipynb): Full end-to-end workflow, from data cleaning to model evaluation and final insights.

## 🛠️ Dependencies

- Python 3.8+
- pandas
- numpy
- scikit-learn
- matplotlib / seaborn
- xgboost (if used)
- jupyter

Install all dependencies using:
```bash
pip install -r requirements.txt
