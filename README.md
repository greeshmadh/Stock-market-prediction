# Stock-market-prediction
This is a project we worked on in our I/O course on Machine learning and data science.

Overview : Aims to predict the closing rate of stock market using the Autoregressive Integrated Moving Average (ARIMA) model. 
Preprocessing : The data was cleaned by handling missing values through imputation techniques such as forward fill or backward fill.
Model Training: The adf_test function was utilized to check for the stationarity of the time series data.The auto_arima function from the pmdarima library was used to automatically select the best ARIMA model for the given time series data.The dataset was split into training and testing sets for model evaluation.The best ARIMA model was determined by auto_arima is fitted to the training data.
Model Evaluation:The performance of the trained model was evaluated using techniques like Mean Absolute Error (MAE), Mean Squared Error (MSE), and Root Mean Squared Error (RMSE) on a validation dataset. 
Prediction: Future closing rates were forecasted using the trained ARIMA model.
