# Predicting Economic Recovery from the COVID-19 Pandemic Using Previous Recessions

A machine learning project that models historical recession patterns to forecast the trajectory of economic recovery following the COVID-19 pandemic.

---

## Overview

The COVID-19 pandemic triggered one of the sharpest economic contractions in modern history. This project leverages historical recession data — including downturns such as the 2008 Global Financial Crisis and the early 2000s recession — to train ML models capable of predicting the shape and timeline of the post-pandemic economic recovery.

By learning from how economies have behaved in previous recessions, the models generate data-driven forecasts for key economic indicators during the COVID-19 recovery period.

---

## Repository Structure

```
├── proj.ipynb       # Main Jupyter Notebook: data processing, modelling, and analysis
├── Report.pdf       # Full project report with methodology and findings
└── .gitignore
```

---

## Methodology

1. **Data Collection** — Historical macroeconomic data (e.g. GDP, unemployment, stock indices) collected for past recessions alongside COVID-19 period data.
2. **Preprocessing** — Data cleaning, normalization, and feature engineering to align recession timelines for comparison.
3. **Modelling** — Multiple ML algorithms applied to learn recovery patterns from historical recessions.
4. **Prediction** — Trained models used to forecast economic recovery metrics for the COVID-19 period.
5. **Evaluation** — Model performance assessed and predictions compared against actual post-pandemic economic data.

---

## Technologies Used

- **Python 3**
- **Jupyter Notebook**
- **pandas** — Data manipulation
- **NumPy** — Numerical computing
- **scikit-learn** — Machine learning algorithms
- **Matplotlib / Seaborn** — Data visualization

---

## Getting Started

### Prerequisites

Make sure you have Python 3 and Jupyter Notebook installed. Then install the required packages:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
```

### Running the Notebook

1. Clone the repository:
   ```bash
   git clone https://github.com/fireball28/Predicting-the-Economic-Recovery-from-the-Covid-19-Pandemic-using-Previous-Recessions.git
   cd Predicting-the-Economic-Recovery-from-the-Covid-19-Pandemic-using-Previous-Recessions
   ```

2. Launch Jupyter Notebook:
   ```bash
   jupyter notebook proj.ipynb
   ```

3. Run all cells sequentially from top to bottom.

---

## Report

A detailed write-up of the project — including the research motivation, full methodology, results, and conclusions — is available in [`Report.pdf`](./Report.pdf).

---

## Results

The models were evaluated on their ability to replicate known recovery trajectories from past recessions and extrapolate trends for the COVID-19 recovery. Key findings and visualizations are documented in both the notebook and the report.

---

## License

This project is open-source and available for educational and research purposes.
