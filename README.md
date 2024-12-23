# Time_Series_Project

**Description:** This project involves the analysis and forecasting of time series data using the ARIMA model. The dataset contains monthly data for pharmaceutical sales from July 1991 to June 2008. The project showcases steps such as data preprocessing, exploratory analysis, stationarity checks, ARIMA model building, and model evaluation, providing a systematic approach to time series forecasting.

**Key Features:**
- **Data Preprocessing:** Converted date column to datetime format and set it as the DataFrame index. Sorted data chronologically to ensure consistency.
- **Exploratory Data Analysis (EDA):** Conducted descriptive statistics and visualized data using histograms and box plots. Analyzed trends, seasonality, and residuals via ETS decomposition.
- **Stationarity Check and Transformation:** Performed Augmented Dickey-Fuller tests. Applied differencing to achieve stationarity.
- **Model Selection and Training:** Determined ARIMA model parameters (p, d, q) using ACF and PACF plots. Split data into training (80%) and testing (20%) sets for robust evaluation.
- **Forecasting and Evaluation:** Developed ARIMA(16, 2, 13) model. Forecasted future values and compared them against actual data using Mean Squared Error (MSE).
- **Visualization:** Plotted actual vs. forecasted values for a clear comparison of model performance.

**Skills Used:** Python, Time Series Analysis, Data Manipulation, Data Visualization, Statistical Analysis, Modeling, Evaluation Matrics

**Conclusion:** This project demonstrates the comprehensive application of time series analysis to forecast monthly pharmaceutical sales. The ARIMA(16, 2, 13) model achieved a Mean Squared Error of 9.85, indicating reasonable predictive accuracy. This workflow emphasizes the importance of preprocessing, stationarity, and parameter tuning in time series forecasting.
