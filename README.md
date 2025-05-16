# sea_level_predictor

This project visualizes historical sea level rise data and uses linear regression to **predict future sea level changes** through the year **2050**. It is based on global average absolute sea level data collected since **1880** by the **US Environmental Protection Agency (EPA)**.

---

##  Project Objectives

- Visualize the trend in global sea level rise using a scatter plot.
- Fit a **linear regression model** using:
  - All available historical data (1880–2014)
  - Recent data from the year 2000 onward
- Predict sea level values through the year 2050.
- Compare both regression lines to understand changing trends.

---

##  Dataset

- **Source**: [EPA Sea Level Data (1880–2014)](https://www.epa.gov/)
- **Download**: [`epa-sea-level.csv`](https://raw.githubusercontent.com/freeCodeCamp/boilerplate-sea-level-predictor/master/epa-sea-level.csv)

---

##  Technologies Used

- Python 3
- Pandas
- Matplotlib
- SciPy (for linear regression)

---

##  Visual Output

- **Scatter Plot**: Historical sea level data
- **Line of Best Fit #1**: Based on full data (1880–2014)
- **Line of Best Fit #2**: Based on recent data (from year 2000)
- **Predictions** extended through year **2050**

---

##  Features

| Feature                           | Description                                            |
|-----------------------------------|--------------------------------------------------------|
|  Historical Trend Plot         | Scatter of observed sea level change over time         |
|  Full Regression Line          | Linear fit over full dataset (1880–2014)               |
|  Recent Regression Line        | Linear fit using data from year 2000 onwards           |
|  Future Prediction             | Extrapolates sea level rise to year 2050               |
|  Plot Output                   | Saved as `sea_level_plot.png`                          |
