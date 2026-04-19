# 🚀 Multivariate Time Series Forecasting using VAR

📌 Project Overview
This project demonstrates a multivariate time series forecasting approach using the Vector Autoregression (VAR) model. The objective is to forecast multiple interdependent time series variables simultaneously and capture their relationships over time.

❗ Problem Statement
In many real-world scenarios, multiple time-dependent variables influence each other (e.g., financial indicators, yield curves). Traditional univariate models fail to capture these interdependencies.

This project addresses:
• Modeling relationships across multiple time series
• Forecasting future values jointly
• Understanding cross-variable influence

🛠️ Approach
🔹 Data Processing
• Timestamp parsing and indexing
• Handling missing values
• Stationarity checks (ADF test)
• Differencing (if required)

🔹 Model Development
• Implemented Vector Autoregression (VAR)
• Optimal lag selection using AIC/BIC
• Model training on multivariate dataset

🔹 Evaluation
• Forecast visualization
• Error analysis (RMSE)
• Residual diagnostics


📊 Results
Metric	Observation
• Model Type	VAR (Multivariate)
• Forecasting	Multi-step ahead prediction
• Performance	Captured inter-variable dependencies effectively
• Stability	Improved after stationarity transformation
Note: Performance depends on data preprocessing and lag selection.


🧰 Tech Stack
• Python
• Pandas, NumPy
• Statsmodels (VAR)
• Matplotlib / Seaborn


💼 Use Cases
📈 Financial market forecasting (yield curves, macro indicators)
⚡ Demand and load forecasting
🏭 Industrial sensor forecasting
📊 Economic data analysis


🔮 Future Improvements
• Integration with LSTM / Deep Learning models
• Feature enrichment with external variables
• Real-time forecasting pipeline

📌 Note
This project is developed as a prototype to demonstrate multivariate forecasting techniques and is not tied to any specific production system.

👤 Author
Subhajit Mondal
Senior Data Scientist | Machine Learning | Time Series
Senior Data Scientist | Machine Learning | Time Series
