# International Debt Data Analysis

## Project Overview

This project aims to analyze international debt data collected by The World Bank. The dataset contains information about the amount of debt (in USD) owed by developing countries across several categories. Using SQL queries, we will answer various questions related to the debt data, such as the total amount of debt, the country with the highest debt, and the average debt across different indicators.

## Dataset Description

The dataset used in this analysis includes the following columns:
- `country_name`: Name of the country.
- `country_code`: Code of the country.
- `indicator_name`: Name of the debt indicator.
- `indicator_code`: Code of the debt indicator.
- `debt`: Amount of debt in USD.

### Sample Data

| country_name | country_code | indicator_name                                               | indicator_code   | debt         |
|--------------|--------------|--------------------------------------------------------------|------------------|--------------|
| Afghanistan  | AFG          | Disbursements on external debt, long-term (DIS, current US$) | DT.DIS.DLXF.CD   | 72894453.7   |
| Afghanistan  | AFG          | Interest payments on external debt, long-term (INT, current US$) | DT.INT.DLXF.CD   | 53239440.1   |
| Afghanistan  | AFG          | PPG, bilateral (AMT, current US$)                             | DT.AMT.BLAT.CD   | 61739336.9   |
| ...          | ...          | ...                                                          | ...              | ...          |


