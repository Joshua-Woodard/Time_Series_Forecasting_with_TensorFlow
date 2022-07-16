# Time_Series_Forecasting_with_TensorFlow
Jupyter Notebook created alongside course study. Includes Milestone Project to predict future price of Bitcoin. Final model mimics N-BEATS algorithm.

## What it covers:
* Importing time series data with Pandas and Python's CSV module
* Create train/test sets of data (includes example of what NOT to do)
* Create plotting function
* Create model experiments:
  * Naive Forecast (baseline)
  * Dense model (window=7, horizon=1)
  * Dense model (window=30, horizon=1)
  * Dense model (window=30, horizon=7)
  * Conv1D
  * LSTM
  * Dense model (using multivariate time series data)
  * N-BEATS algorithm
  * Ensemble model (stacking different models together)
* Make predictions on models
* Plotting prediction intervals of our ensemble
* Make predictions into future using N-BEATS algorithm
* Plot future forecasts
* Compare models
* Why forecasting is BS (sometimes) -> the Turkey Problem
