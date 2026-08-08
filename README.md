# ML Internship Projects

Three end-to-end machine learning projects, each following the internship project brief step by step. All notebooks are already executed — plots, tables, and metrics are baked in, so they render fully on GitHub without needing to be re-run.

## Contents

| Notebook | Project | Techniques |
|---|---|---|
| `01_aqi_analysis_forecasting.ipynb` | Air Quality Index Analysis & Forecasting — Indian Cities | EDA, seasonality analysis, ARIMA, Facebook Prophet, model comparison, policy recommendations |
| `02_titanic_survival_prediction.ipynb` | Titanic Survival Prediction | Data cleaning, feature engineering, one-hot encoding, Logistic Regression |
| `03_handwritten_digit_recognition.ipynb` | Handwritten Digit Recognition | Normalization, Random Forest, SVM, confusion matrices |

`data/` — daily AQI + pollutant (PM2.5, PM10, NO2, SO2, CO, O3) datasets for Delhi, Mumbai, Bangalore, Chennai, and Hyderabad, used by the AQI notebook. (Titanic and Digits notebooks pull their data automatically from `seaborn`/`sklearn`, no files needed.)

## How to run

**No local IDE needed** — open in [Google Colab](https://colab.research.google.com):
1. File → Upload notebook → select the `.ipynb` file.
2. For the AQI notebook only: create a `data` folder in the Colab file sidebar and upload the 5 CSVs from this repo's `data/` folder, then run `!pip install prophet` in a new first cell.
3. Runtime → Run all.

## Tools & Environment
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Statsmodels (ARIMA), Prophet
