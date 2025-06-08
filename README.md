# Retail Sales Forecasting

This project forecasts weekly sales for retail stores using machine learning (XGBoost).

## Dataset

- `train.csv`
- `test.csv`
- `features.csv`
- `stores.csv`

Place these files in the `data/` directory.

## Requirements

Install the Python dependencies with:

```bash
pip install -r requirements.txt
```

## Running the Notebook

Start Jupyter Notebook and open:

```bash
jupyter notebook notebooks/retail_sales_forecasting.ipynb
```

The notebook performs:
- Data merging and preprocessing
- Feature engineering
- Model training and evaluation
- Predictions on the test set

## Notes

- Dataset files are **not included** due to size; download them separately and place inside `data/`.


# 🛒 Retail Sales Forecasting

This project predicts **weekly sales** for a retail chain using machine learning techniques like **Random Forest Regression**. It uses historical data along with external features like **temperature, fuel price, holidays, and CPI**.

---

## 📁 Dataset Files

The dataset comes from Walmart and includes the following files:

- `train.csv` – Historical weekly sales data for each department in each store
- `test.csv` – Data to make sales predictions
- `features.csv` – External factors (e.g., Temperature, CPI, Fuel Price, Holiday Flag)
- `stores.csv` – Metadata about store type and size

---

## 📈 Methodology

Steps followed in the project:

1. Merged all CSV files into one structured dataset
2. Created lag features (sales 1 and 4 weeks ago) to help the model learn patterns
3. Cleaned missing data using mean imputation
4. Trained a **Random Forest Regressor** model on the cleaned dataset
5. Evaluated performance using **Root Mean Squared Error (RMSE)**

---

## 🚀 Run in Google Colab

You can try the notebook directly in Colab:

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Sarthak451/Retail-sales-forecasting-/blob/main/notebooks/retail_sales_forecasting.ipynb)

---

## 🧪 Notebook File

The complete machine learning workflow is in:

notebooks/retail_sales_forecasting.ipynb


---

## ⚙️ Installation

To install the required Python packages:

```bash
pip install -r requirements.txt
