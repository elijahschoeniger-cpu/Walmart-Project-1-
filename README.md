# Walmart-Project-1-
Shared repository for project 1 work 
# [Project 1 - Walmart ]

**DS2002 · Fall 2026 · [Midterm | Capstone]**

## Team

| Name | GitHub | Role / main contributions |
|------|--------|---------------------------|
| Elijah | elijahschoeniger | Data Cleaning |
| AJ  | pizzeman | API|
| Sophie | Sophieli0113 | Visualization |

## Summary

The goal of this project was to analyze the transaction data for Walmart superstores in Florida during Hurricane Helene in 2024. Through the process of ETL, cleaned data paired with weather data pulled through OpenMeteo API revealed how the hurricane affected sales. The questions we aimed to answer were:
1. What product categories were most affected by the hurricane?
2. Did the stores closest to landfall have the highest increase in sales?
3. Does the weather data serve as a predictor?
4. Which distributors should supply the products that increased in sales?


## Data

| File | Source | Notes |
|------|--------|-------|
|distribution_centers.csv | Given | Contains location of all distribution centers |
|inventory_and_sales.db | Given | Contains inventory |
|product_catalog.csv | Given | Contains all different catalog types for walmart store |
|store_locations.csv | Given | Locations of brick-and-motors in the Florida region |
|walmart_transactions.csv | Given | Contains all transactions for a given day |

External API used: **OpenMeteo** — base URL: `https://open-meteo.com/`

## How to run

1. Open `[notebook].ipynb` in Kaggle/Colab
2. Run all cells top to bottom
3. (If cloud) authenticate with your `@virginia.edu` account when prompted
4. Check outputs

## Key findings

- Entertainment increased significantly in sales
- Weather serves as a predictor for when sales will increase
- Location of store relative to landfall had insignificant impact on sales


## Recommendation

Start restocking about a week before the storm hits, focus on Pop-Tarts, water, batteries and flashlights, stock a few more board games, an use the closest distribution center for each store without overloading Jackonville

## Reflection

Section 7 of notebooks/team_notebook.ipynb
