# Stock Price Prediction Using LSTM
This project aims to predict the stock prices of Google (GOOG) using the Long Short-Term Memory (LSTM) model. The primary objective is to build an accurate predictive model that can forecast future stock prices based on historical data, aiding investors and analysts in making informed decisions.

**Dataset Description**
The dataset, GOOG.csv, contains historical stock prices of Google, including the date, opening price, highest price, lowest price, closing price, and trading volume. This comprehensive dataset is crucial for building a reliable predictive model.

**Project Overview**
Data Pre-processing: Imported essential libraries, loaded the dataset, inspected data, checked for missing values, and formatted the date column.
Data Exploration and Cleaning: Focused on the 'close' column, identified outliers, and visualized historical closing prices.
Exploratory Data Analysis: Created subplots, calculated a 50-day moving average, and analyzed the Relative Strength Index (RSI).
Model Preparation: Normalized closing prices, split data into training and testing sets, and reshaped data for the LSTM model.
Model Building and Training: Constructed, compiled, and trained the LSTM model, generating predictions for both training and testing datasets.
Model Evaluation and Visualization: Visualized actual vs. predicted stock prices and calculated the Root Mean Squared Error (RMSE).
Model Improvement: Built an enhanced LSTM model with dropout layers, applied K-fold cross-validation, and compared RMSE values.
Final Visualization: Monitored training and validation loss over epochs.

**Evaluation Metrics**
Initial RMSE: 66.33
Average RMSE after K-Fold Cross-Validation: 0.01096

**Summary and Conclusion**
The LSTM model successfully predicted Google's stock prices, showcasing the potential of deep learning in time series forecasting. The insights gained can help investors make data-driven decisions, though future improvements can include more features, advanced techniques, and real-time prediction systems.

**Limitations and Future Work**
Inclusion of More Features: Incorporating macroeconomic indicators or sentiment analysis.
Advanced Techniques: Exploring ensemble learning or hybrid models.
Real-Time Prediction: Implementing real-time prediction systems.

**Appendix**
Code Snippets: Detailed code for data pre-processing, model training, and evaluation.
Visualizations: Stock price trends, model predictions, and error metrics.
