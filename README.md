📊 Aviation History Data Preprocessing
This repository contains a Python Jupyter Notebook that performs data preprocessing on an aviation dataset consisting of historical data from 1970 to 2020.

🔧 Features of the Code:
Loads the dataset from CSV format using pandas

Cleans the data by:

Dropping columns with all missing values (like 2020)

Removing duplicate rows

Handling missing values using interpolation

Provides basic insights using:

.head(), .info(), .describe()

Missing value summary

Saves the cleaned data to a new CSV file for further analysis or modeling

📁 File:
preproc.ipynb: Contains all preprocessing steps, ready to run in Jupyter Notebook

✅ Requirements:
Python 3.x

pandas

numpy (optional for further steps)

matplotlib / seaborn (optional for visualizations)
