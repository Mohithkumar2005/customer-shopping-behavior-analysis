# Customer Shopping Behavior Analysis

An end-to-end portfolio project exploring customer shopping behavior with Python, SQL, and Power BI. I built this project as a learning exercise while following the tutorial and project reference below, then organized the supplied notebook, cleaned dataset, and dashboard into a reproducible repository.

## Project contents

- `notebooks/Customer_Behaviour_Shopping_Analysis.ipynb` - data exploration, cleaning, feature engineering, and preparation steps. Database connection cells containing local credentials were removed from this public copy.
- `data/cleaned_customer_shopping_behavior.csv` - cleaned data used by the analysis.
- `sql/customer_behavior_analysis.sql` - Ten MySQL 8 analysis queries supplied for this project.
- `dashboard/customer_behavior_dashboard.pbix` - Power BI dashboard.
- `docs/` - project brief and analysis report PDFs.

## Run the notebook

Install Python with pandas and Jupyter, then open the notebook. The notebook expects the cleaned CSV at `data/cleaned_customer_shopping_behavior.csv`; if running cells that read it from the notebook directory, adjust the relative path to `../data/cleaned_customer_shopping_behavior.csv`.

## Run the SQL queries

Import the cleaned CSV into MySQL as a table named `customer`, then run `sql/customer_behavior_analysis.sql`. The script uses common table expressions and a window function, so MySQL 8.0 or later is recommended.

## Open the dashboard

Open the `.pbix` file in Microsoft Power BI Desktop. If Power BI prompts for a data source, point it to the included cleaned CSV and refresh the model.

## Reference

The project was completed as a learning exercise based on the tutorial/repository that inspired it: [amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI](https://github.com/amlanmohanty1/customer-trends-data-analysis-SQL-Python-PowerBI). The linked repository belongs to its original author.


