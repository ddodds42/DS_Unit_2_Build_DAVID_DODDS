# DS_Unit_2_Build_DAVID_DODDS

## Python notebooks are in the following files:
- Baseline.ipynb
- HDI_Forecasts.ipynb
- MV_Linear_Models.ipynb
- MV_Tree_Models.ipynb
- Nation_trend_plotter.ipynb
- State_Fail_event_forecasts.ipynb
- Train_test_splits.ipynb

## Master_MELT_github.csv is the master dataset engineered from the root datasets
It is split into the following datasets for trainin, validation, forecasting, etc.:
- explore_github.csv
- forecast_20s_github.csv
- semi_forecast_github.csv
- test_github.csv
- train_github.csv
- val_github.csv

Each jpg file is a screenshot of the most notable data visualizations from the predictive models.

Files with _imp_ in the name were interpolated with default extrapolation in my previous build week project called "Measuring Why Nations Fail".

Files with _int_ext_ in the name are interpolated by time series mean, then extrapolited using SKLearn Curve extrapolation.

Also included is the Word File of the blog draft analysis of these predictive models,
and an excel file which scores each feature's importance accross 5 models after validation.
