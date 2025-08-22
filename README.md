Using a variety of models to predict short & long term CPI first
Simple endogenous CPI w/ SARIMA
SARIMA: Weighted past average accounting for seasonality
HRNN: Hierarchical, depends on subdatasets
Exogenous prediction w/tree models & deep learning
Using: Import, housing, oil, shipping, fed rates (using various lagging indicators/weights)
Trees are a set of easily retrainable models, some linear
Deep learning to identify macroeconomic state, loop back to adjust coefficients
Combining predictions
Output probability graph, sources of inflation from backtesting

NOTE: WIP, code may not compile but the general idea is here
