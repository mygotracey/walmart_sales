# Walmart Sales Data Analysis

## Project Overview

This project focuses on performing data visualization and analysis on a Walmart weekly sales dataset. The goal is to uncover trends, patterns, and key insights that influence sales performance across different stores and over time, including the impact of holidays and various economic factors.

## Dataset

The dataset used for this analysis is `walmart_sales.csv`, sourced from Kaggle. It contains weekly sales data for various Walmart stores, along with external factors suchs:

* **Store**: Store ID
* **Date**: Date of the weekly record
* **Weekly_Sales**: Sales for the given week
* **Holiday_Flag**: Indicates if the week was a holiday week (1) or not (0)
* **Temperature**: Average temperature in the region
* **Fuel_Price**: Cost of fuel in the region
* **CPI**: Consumer Price Index
* **Unemployment**: Unemployment rate

## Analysis Goals

* Understand the distribution of weekly sales.
* Analyze sales trends over time (overall, monthly, yearly).
* Identify the impact of holiday weeks on sales.
* Compare sales performance across different stores.
* Explore relationships between external factors (Temperature, Fuel Price, CPI, Unemployment) and weekly sales.
* Derive actionable insights from the data.

## Project Structure

The analysis is structured into several key parts:

1.  **Setup and Data Loading**: Importing necessary libraries and loading the `walmart_sales.csv` dataset into a pandas DataFrame.
2.  **Data Cleaning & Feature Engineering**:
    * Converting the 'Date' column to datetime objects for time-series analysis.
    * Extracting new features like `Year`, `Month`, `Week`, `Day`, `DayOfWeek`, and `Quarter` from the 'Date' column to facilitate seasonal analysis.
3.  **Data Visualization**: Creating various plots using `matplotlib` and `seaborn` to visually explore the data, including histograms, line plots, bar plots, box plots, scatter plots, and correlation heatmaps.
4.  **Data Analysis and Storytelling**: Deriving statistical insights and summarizing key findings from the visualizations and raw data into a coherent narrative.

## How to Run the Analysis

This project is designed to be run in a **Jupyter Notebook** environment.

1.  **Ensure Jupyter Notebook is Installed:**
    If you don't have Jupyter Notebook installed, you can do so via Anaconda (recommended for data science setup) or pip:
    * Using pip: `pip install notebook`
    * Using Conda: `conda install notebook`

2.  **Place Dataset:**
    Ensure your `walmart_sales.csv` file is in the **same directory** as your Jupyter Notebook file (e.g., `sales.ipynb`).

3.  **Open Jupyter Notebook:**
    * Open your terminal or command prompt.
    * Navigate to the directory where you saved your `sales.ipynb` and `walmart_sales.csv` files using `cd`.
    * Run the command: `jupyter notebook`
    * This will open the Jupyter interface in your default web browser.

4.  **Open the Notebook:**
    In the Jupyter interface, you will see a list of files. Click on `sales.ipynb` to open the notebook in a new tab.

5.  **Run Cells:**
    Execute each code cell sequentially within the notebook. The output will include printed insights and generated plots.

## Key Insights (Summary)

* **Sales Seasonality**: Clear peaks in sales were observed during specific months, often corresponding to holiday periods (e.g., end-of-year holidays).
* **Holiday Boost**: Holiday weeks consistently show higher average weekly sales compared to non-holiday weeks.
* **Store Performance Variance**: Significant differences exist in total sales across various Walmart stores, indicating varying local market conditions or store operational efficiencies.
* **External Factor Influence**: Correlations suggest that external economic factors like temperature, fuel price, CPI, and unemployment rate have varying degrees of influence on weekly sales. For instance, (mention specific findings like "higher fuel prices tend to correlate with slightly lower sales" or "higher CPI might correlate positively/negatively depending on your findings").

## Technologies Used

* Python
* Pandas (for data manipulation)
* NumPy (for numerical operations)
* Matplotlib (for plotting)
* Seaborn (for enhanced visualizations)
[Walmart_Sales.csv](https://github.com/user-attachments/files/20348456/Walmart_Sales.csv)
