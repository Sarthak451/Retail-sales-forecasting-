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
