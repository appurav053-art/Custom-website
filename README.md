**House Price Prediction** 🏠

This project implements a machine learning regression model to predict median house values in California districts. It uses the XGBoost Regressor and follows a full data science workflow, including exploratory data analysis, feature engineering, and geographic visualization.


📊 **Project Overview**

The goal of this project is to predict the MedHouseVal (Median House Value) based on 8 economic and geographic features from the 1990 U.S. Census data.


**Key Features**:
*Data Source*: Scikit-learn California Housing Dataset
*Algorithm*: XGBoost (Extreme Gradient Boosting)
*Evaluation Metrics*: R-Squared ($R^2$) and Mean Absolute Error (MAE)
*Visualizations*: Correlation heatmaps, error distribution plots, and interactive geographic maps.


🛠️ **Installation & Usage**
*Clone the repository*:
git clone https://github.com/MYoussef885/House_Price_Prediction.git

*Install dependencies*:
pip install numpy pandas matplotlib seaborn xgboost sklearn plotly

**Run the Notebook**:
Open House_Price_Prediction.ipynb in Google Colab or Jupyter Notebook and run all cells.


📈 **Model Performance**
After hyperparameter tuning ($n\_estimators=1000$, $learning\_rate=0.05$), the model achieved:

*Training $R^2$ Score*: ~0.94Test
*$R^2$ Score*: ~0.83Mean 
*Absolute Error*: ~0.31 ($31,000 USD)





Training $R^2$ Score: ~0.94Test $R^2$ Score: ~0.83Mean Absolute Error: ~0.31 ($31,000 USD)📈 Model PerformanceAfter hyperparameter tuning ($n\_estimators=1000$, $learning\_rate=0.05$), the model achieved:Training $R^2$ Score: ~0.94Test $R^2$ Score: ~0.83Mean Absolute Error: ~0.31 ($31,
