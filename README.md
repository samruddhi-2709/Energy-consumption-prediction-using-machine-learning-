# Energy-consumption-prediction-using-machine-learning-

This project focuses on Energy Consumption Prediction for an electrical blower machine. The dataset used features time-series data recorded at 10-15 minute intervals using IoT devices. Key characteristics of the dataset include:

Energy Measurement: Energy consumption is calculated between current and previous timestamps in kilowatt-hours (KWh).
Operational State: Energy values below 0.5 KWh indicate that the machine was off during the respective time slot.
Stationary Series: The dataset represents stationary time-series data for forecasting.
Key Features of the Notebook:
Time-Series Decomposition: Both additive and multiplicative decompositions are applied to analyze the components of the time series.
AutoRegression Models: Implements AR-based forecasting methods to predict future energy consumption trends.
Applications:
This project demonstrates predictive analytics for industrial IoT data, enabling better energy management and operational efficiency.
