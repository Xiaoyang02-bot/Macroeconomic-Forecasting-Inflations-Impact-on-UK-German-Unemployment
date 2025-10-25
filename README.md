# Econometric Forecasting of Unemployment Rates (Stata to Python)

**Author:** Xiaoyang Ma
**GitHub Profile:** https://github.com/Xiaoyang02-bot

---

This project replicates an econometric time-series analysis, originally conducted in Stata, using Python. It builds, evaluates, and forecasts unemployment rates for the UK (GBR) and Germany (DEU) using Autoregressive Distributed Lag (ARDL) and Autoregressive (AR) models.

This analysis is contained entirely in the `Econometrics-Forecasting-Project.ipynb` file.

## Project Goal

The objective is to determine whether inflation data improves unemployment forecasts. The analysis involves:
1.  **Data Preparation:** Loading, cleaning, and visualizing time-series data.
2.  **Model Selection (In-Sample):** Building and comparing selected ARDL(p,q) and AR(p) models for each country, using AIC and Breusch-Godfrey tests.
3.  **Forecasting (Out-of-Sample):** Using the selected models to forecast unemployment rates for the 2016q1-2019q4 period.
4.  **Evaluation:** Assessing forecast accuracy using Mean Squared Error (MSE) and/or Mean Absolute Error (MAE).

## Skills & Tools Used

* **Python 3**
* **Pandas:** For data loading (from `.dta`), manipulation, and creating lagged variables.
* **Statsmodels:** For OLS regression, Breusch-Godfrey serial correlation tests, and generating out-of-sample forecasts with confidence intervals.
* **Matplotlib:** For all data visualization, including time-series plots, ACF/PACF plots, and forecast plots.
* **Scikit-learn (sklearn):** For calculating forecast accuracy metrics (MAE/MSE).
* **Jupyter Notebook:** As the environment for analysis and presentation.

## Key Findings (Summary)

* **DEU (Germany):** Models such as ARDL(2,2) and AR(2) were evaluated.
* **GBR (UK):** Models such as ARDL(1,3), ARDL(2,3), and AR(4) were evaluated.
* **Forecast Comparison:** The project generates head-to-head plots comparing the forecast accuracy of the selected models against the actual out-of-sample data.

## How to Run This Project

1.  Ensure you have Anaconda or Python installed with the libraries listed above (`pandas`, `statsmodels`, `matplotlib`, `sklearn`).
2.  Clone or download this repository.
3.  Place the `oecd_phillips_assignment.dta` file in the same directory as the notebook.
4.  Open and run the `Econometrics-Forecasting-Project.ipynb` notebook from top to bottom.
