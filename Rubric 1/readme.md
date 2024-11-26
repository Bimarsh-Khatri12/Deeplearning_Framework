This project involves prediction of streamflow in multiple time series.This project aims to predict daily streamflow values using a Long Short-Term Memory (LSTM) neural network. It leverages weather and soil data to model the time series patterns and predict future streamflow values effectively.
The approach for the project involves following steps:

**1. Data Preprocessing:**
-Selected relevant features from the dataset (e.g., temperature, pressure, precipitation, etc.).
-Encoded the date feature numerically for processing.
-Scaled the data using MinMaxScaler to normalize feature ranges.

**2. Sequence Creation:**
-Converted the data into sequences with a fixed window length (30 days) for time series modeling.

**3. Model developement**
-Built and trained an LSTM neural network with two LSTM layers and one Dense layer to predict streamflow.

**4.Evaluation and Visualization:**
-Predicted streamflow values for test data and calculated the Mean Squared Error (MSE).
-Plotted actual vs. predicted values to visualize model performance.

**Approach**
**Feature Engineering:** Incorporated weather-related attributes for predicting streamflow.
**Time Series Modeling:** Used LSTM to learn sequential patterns and make forecasts.
**Evaluation Metrics:** Assessed the model's accuracy with MSE and visualized predictions with line plots.

**Note: The dataset used here is real dataset collected from different checkpoint of a streamflow in Nepal**
