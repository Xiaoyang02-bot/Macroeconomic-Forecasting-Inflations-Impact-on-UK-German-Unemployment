# Econometric Forecasting of Unemployment Rates (Stata to Python)

**Author:** Xiaoyang Ma  
**GitHub Profile:** https://github.com/Xiaoyang02-bot

## Academic Integrity and Project Context

This project is a **personal Python implementation** of an econometric analysis assignment for the "Applied Econometrics II" module at the University of Nottingham.

* **Original Assignment:** The original coursework was a **group project** completed using **Stata**, as per the module requirements.
* **Personal Contribution:** All Python code, analysis, and visualizations in the `.ipynb` notebook are my **sole, original work**. This was an independent, self-directed project undertaken *in addition* to the group assignment to demonstrate my proficiency in the Python data science ecosystem.
* **Disclaimer:** To maintain strict academic integrity, the original university course requirements, official assignment brief, and the original group's Stata report are **not** included in this repository.

## Project Goal

This analysis investigates whether inflation data can improve the accuracy of unemployment rate forecasts for the UK (GBR) and German (DEU) economies.

The workflow involves:
1.  **Data Preparation:** Loading, cleaning, and visualizing the time-series data.
2.  **Model Selection (In-Sample):** Building and comparing Autoregressive (AR) and Autoregressive Distributed Lag (ARDL) models, using AIC and Breusch-Godfrey tests for selection.
3.  **Forecasting (Out-of-Sample):** Using the selected models to forecast unemployment rates for the 2016q1-2019q4 period.
4.  **Evaluation:** Assessing forecast accuracy using Mean Squared Error (MSE) and Mean Absolute Error (MAE).

## Skills & Tools Used

* **Python 3**
* **Pandas:** For data loading (from `.dta`), manipulation, and creating lagged variables.
* **Statsmodels:** For OLS regression, Breusch-Godfrey serial correlation tests, and generating out-of-sample forecasts.
* **Matplotlib:** For all data visualization, including time-series plots, ACF/PACF plots, and forecast plots.
* **Scikit-learn (sklearn):** For calculating forecast accuracy metrics (MAE/MSE).
* **Jupyter Notebook:** As the environment for analysis and presentation.

## Data Source and Availability

* The data used (`oecd_phillips_assignment.dta`) is based on **publicly available data** from the OECD.
* It **is included** in this repository to ensure the Python analysis is fully replicable.

## How to Run This Project

1.  Ensure you have Anaconda or Python installed with the libraries listed above.
2.  Clone or download this repository.
3.  Place the `oecd_phillips_assignment.dta` file in the same directory as the notebook.
4.  Open and run the `Econometrics-Forecasting-Project.ipynb` notebook from top to bottom.
