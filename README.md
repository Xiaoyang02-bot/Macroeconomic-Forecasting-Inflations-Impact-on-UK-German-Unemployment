# Econometric Forecasting of Unemployment Rates (Stata to Python)

**Author:** Xiaoyang Ma
**GitHub Profile:** https://github.com/Xiaoyang02-bot

---

## Academic Integrity and Project Context

[cite_start]This project is a **personal Python implementation** of an econometric analysis assignment for the "Applied Econometrics II" module at the University of Nottingham[cite: 20].

The original assignment was completed using Stata. The purpose of this repository is to:
1.  **Demonstrate Technical Proficiency:** Showcase my ability to independently replicate a complex econometric workflow using the Python (Pandas, Statsmodels, Matplotlib) ecosystem.
2.  **Create a Portfolio Piece:** Translate academic coursework into a practical, well-documented data science project.

All Python code in the `.ipynb` notebook is my original work.

## Project Goal

[cite_start]This analysis investigates whether inflation data can improve the accuracy of unemployment rate forecasts for the UK (GBR) and German (DEU) economies[cite: 22].

The workflow involves:
1.  **Data Preparation:** Loading, cleaning, and visualizing the time-series data.
2.  [cite_start]**Model Selection (In-Sample):** Building and comparing Autoregressive (AR) and Autoregressive Distributed Lag (ARDL) models[cite: 23], using AIC and Breusch-Godfrey tests for selection.
3.  [cite_start]**Forecasting (Out-of-Sample):** Using the selected models to forecast unemployment rates for the 2016q1-2019q4 period[cite: 24].
4.  **Evaluation:** Assessing forecast accuracy using Mean Squared Error (MSE) and Mean Absolute Error (MAE).

## Skills & Tools Used

* **Python 3**
* **Pandas:** For data loading (from `.dta`), manipulation, and creating lagged variables.
* **Statsmodels:** For OLS regression, Breusch-Godfrey serial correlation tests, and generating out-of-sample forecasts with confidence intervals.
* **Matplotlib:** For all data visualization, including time-series plots, ACF/PACF plots, and forecast plots.
* **Scikit-learn (sklearn):** For calculating forecast accuracy metrics (MAE/MSE).
* **Jupyter Notebook:** As the environment for analysis and presentation.

## Data Source

The data used (`oecd_phillips_assignment.dta`) is based on **publicly available data** from the OECD. It is included in this repository to ensure the analysis is fully replicable.

## How to Run This Project

1.  Ensure you have Anaconda or Python installed with the libraries listed above (`pandas`, `statsmodels`, `matplotlib`, `sklearn`).
2.  Clone or download this repository.
3.  Place the `oecd_phillips_assignment.dta` file in the same directory as the notebook.
4.  Open and run the `Econometrics-Forecasting-Project.ipynb` notebook from top to bottom.
