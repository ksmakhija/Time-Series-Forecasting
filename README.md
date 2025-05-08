Sparkling Wine Sales Time Series Analysis
This project performs an in-depth time series analysis on monthly sparkling wine sales data. The goal is to understand trends, seasonality, and to forecast future sales using various time series forecasting models.

📁 Dataset
File: Sparkling.csv
Columns:

YearMonth: Date in YYYY-MM format.

Sparkling: Monthly sparkling wine sales.

Data Summary:

Time range: 1980-01 to ~1995

Observations: 187 rows

Mean sales: 2402 units

Sales range: 1070 to 7242 units

📊 Project Workflow
1. Data Loading & Preprocessing
Parsed the YearMonth column as datetime.

Set the datetime as index to treat it as a time series.

2. Visualization
Time series line plot to show trends and seasonality.

Seasonal decomposition using statsmodels.

3. Modeling Approaches
Applied multiple forecasting models:

Simple Exponential Smoothing

Holt's Linear Trend Method

Holt-Winters Exponential Smoothing (Additive & Multiplicative Seasonality)

4. Evaluation Metrics
RMSE (Root Mean Square Error)

MAPE (Mean Absolute Percentage Error)

🛠 Libraries Used
pandas, numpy

matplotlib, seaborn

statsmodels

sklearn.metrics

IPython.display

📈 Results
The Holt-Winters models (especially with additive and multiplicative seasonality) provided a strong fit to the data, capturing both trend and seasonal patterns.

🧠 Author
Kanchan Narsinghani


