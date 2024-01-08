Forecasting 30-Day Volatility of the S&P 500: A Comparison of LSTM and GARCH Models
Overview
This paper presents a comprehensive study comparing various Long Short-Term Memory (LSTM) models and the Generalized Autoregressive Conditional Heteroskedasticity (GARCH) model in forecasting the 30-day volatility of the S&P 500 index. We focus on evaluating the accuracy and stability of these models, with a particular emphasis on the potential of LSTM models in financial market predictions.

Key Findings
Simplicity and Effectiveness of Plain LSTM: Our results indicate that the plain LSTM model, despite its simplicity, outperforms more complex models in terms of forecasting accuracy.
CNN on Polar Encodings: We explore the use of Convolutional Neural Networks (CNN) on polar encodings, which shows promising potential.
Comparison with 2D-CNN-LSTM Architecture: While the 2D-CNN-LSTM architecture can achieve lower Mean Absolute Percentage Error (MAPE) figures, its estimates tend to be more unstable compared to the plain LSTM model.
Contribution to Existing Studies: This study supplements existing research by demonstrating the effectiveness of deep learning models, particularly LSTM, in making accurate predictions in financial markets.
Data and Methodology
Data Source: The study uses historical data of the S&P 500 index.
Models Evaluated:
Plain LSTM
LSTM with CNN on polar encodings
2D-CNN-LSTM
GARCH model
Results
Performance Metrics: The models are evaluated based on their forecasting accuracy, with a focus on Mean Absolute Percentage Error (MAPE).
LSTM vs. GARCH: The plain LSTM model shows superior performance compared to the traditional GARCH model in terms of forecasting accuracy.
Stability Analysis: An analysis of the stability of the predictions is provided, highlighting the trade-off between accuracy and stability in complex models.
Conclusions
The findings of this study suggest that while more complex LSTM models, such as those incorporating CNN or polar encodings, can offer improved accuracy, they may also introduce instability in predictions. The plain LSTM model, in contrast, provides a balance of accuracy and stability, making it a compelling choice for forecasting the volatility of financial markets.
