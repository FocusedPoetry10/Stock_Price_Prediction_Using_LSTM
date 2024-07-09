# Stock Price Prediction Using LSTM

This project aims to predict the stock prices of Google (GOOG) using the Long Short-Term Memory (LSTM) model. The primary objective is to build an accurate predictive model that can forecast future stock prices based on historical data, aiding investors and analysts in making informed decisions.

## Dataset Description
The dataset, `GOOG.csv`, contains historical stock prices of Google, including the date, opening price, highest price, lowest price, closing price, and trading volume. This comprehensive dataset is crucial for building a reliable predictive model.

## Project Overview
1. **Data Pre-processing**
   - Imported essential libraries
   - Loaded the dataset
   - Inspected data
   - Checked for missing values
   - Formatted the date column

2. **Data Exploration and Cleaning**
   - Focused on the 'close' column
   - Identified outliers
   - Visualized historical closing prices

3. **Exploratory Data Analysis**
   - Created subplots
   - Calculated a 50-day moving average
   - Analyzed the Relative Strength Index (RSI)

4. **Model Preparation**
   - Normalized closing prices
   - Split data into training and testing sets
   - Reshaped data for the LSTM model

5. **Model Building and Training**
   - Constructed, compiled, and trained the LSTM model
   - Generated predictions for both training and testing datasets

6. **Model Evaluation and Visualization**
   - Visualized actual vs. predicted stock prices
   - Calculated the Root Mean Squared Error (RMSE)

7. **Model Improvement**
   - Built an enhanced LSTM model with dropout layers
   - Applied K-fold cross-validation
   - Compared RMSE values

8. **Final Visualization**
   - Monitored training and validation loss over epochs

## Summary and Conclusion
The LSTM model successfully predicted Google's stock prices, showcasing the potential of deep learning in time series forecasting. The insights gained can help investors make data-driven decisions, though future improvements can include more features, advanced techniques, and real-time prediction systems.

## Limitations and Future Work
- **Inclusion of More Features**: Incorporating macroeconomic indicators or sentiment analysis.
- **Advanced Techniques**: Exploring ensemble learning or hybrid models.
- **Real-Time Prediction**: Implementing real-time prediction systems.
