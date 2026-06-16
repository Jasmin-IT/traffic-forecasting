# Traffic Forecast - Time Series Analysis

This repository contains a time series forecasting project to predict traffic on the JetRail propulsion transport network over the next 7 months.

## Dataset Information

Unicorn Ventures is considering investing in JetRail, a new form of high-speed jet propulsion transportation. The investment is viable only if JetRail gets more than 1 million monthly users within the next 18 months. This project builds a forecasting model to help them make an informed investment decision.

### Attribute Information:
* **Datetime** - Date and time of the day
* **Count** - Count of the vehicle

* **Download Link:** [Analytics Vidhya Time Series Practice Problem](https://datahack.analyticsvidhya.com/contest/practice-problem-time-series-2/)

## Requirements

The project requires the following libraries:
* `pandas`
* `numpy`
* `matplotlib`
* `scikit-learn`
* `prophet`

To install the required dependencies, run:
```bash
pip install -r requirements.txt
```

## How to Run

1. Clone this repository.
2. Ensure you have the dataset `Traffic data.csv` in the project root directory.
3. Install all dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook "Traffic Forecast - Time Series Analysis.ipynb"
   ```
5. Execute all cells in the notebook.

## Model / Algorithms

* **Prophet**: A procedure for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality, plus holiday effects.
