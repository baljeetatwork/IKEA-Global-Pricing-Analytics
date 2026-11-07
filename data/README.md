# Data

## Raw data (not included)

The raw file `IKEA_product_catalog.csv` (about 120 MB, 401,046 product–country listings across 46 countries) is larger than GitHub's 100 MB file limit, so it is not stored here.

Download it from Kaggle: [IKEA Global Product Catalog and Price 2026](https://www.kaggle.com/datasets/ranjithpanicker/ikea-global-product-catalog-and-price-2026)

## Processed data (included)

| File | Rows | What it is |
|---|---|---|
| `processed/ikea_eur_cleaned.csv` | 105,671 | Cleaned, model-ready Eurozone listings |
| `processed/fact_price.csv` | 105,671 | Power BI fact table: actual price, predicted price, residual and percentage error per listing |
| `processed/dim_category.csv` | 16 | Category dimension (top 15 categories plus "Other") |
| `processed/dim_country.csv` | 13 | Country dimension (Eurozone markets) |

All processed files are produced by `notebooks/IKEA_price_analysis.ipynb`.
