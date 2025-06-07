# Sales Analytics with Spark and Python

This is a project where I explored some sales data using Spark and Python. The goal was to load several CSV files, clean them up, and figure out trends by year. I used PySpark for the heavy lifting and Seaborn to make the charts.

## What I did

- Loaded a few `.csv` files using Spark
- Set up a schema manually so the columns would make sense
- Cleaned the data a bit and pulled out the year from the order date
- Looked at revenue totals by year
- Made some simple visual charts using Python (Seaborn and Matplotlib)

## Tools I used

- Spark (PySpark)
- Pandas
- Seaborn
- Matplotlib

This was done inside a Databricks notebook, but if you have Spark running locally, it should work there too.

## Files here

- `Sales_Analytics_With_Seaborn.html` – the notebook output with code, charts, and notes
- `README.md` – you're reading it

## Running this yourself

If you're running this somewhere else (like Jupyter), you might need to install the Python libraries first:

```bash
pip install pandas seaborn matplotlib pyspark
