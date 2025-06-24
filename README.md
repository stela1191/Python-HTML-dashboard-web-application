# Automobile Sales Statistics Dashboard

This project is an interactive data visualization dashboard built with Dash and Plotly. It explores historical automobile sales data from 1980 to 2023, focusing on trends in sales and advertising, especially during recession periods. To compete this project, I followed instructions and lessons from IBM Data Vizualisations in Python course, which is a part of IBM Data Analayst Professional Certificate, which I am currently learning from on Coursera.

## Dashboard Overview

The dashboard allows users to switch between two types of reports:

### 1. Yearly Statistics
- Visualizes average automobile sales by year
- Displays monthly sales trends
- Shows average vehicles sold by type for the selected year
- Breaks down advertising expenditure by vehicle type

### 2. Recession Period Statistics
- Tracks average automobile sales during recession years
- Compares sales across different vehicle types
- Shows advertising budget distribution during recessions
- Analyzes the impact of unemployment on vehicle type and sales

The "Year" dropdown is enabled only when **Yearly Statistics** is selected.

## Data Source

The dataset is provided by [IBM Developer Skills Network](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DV0101EN-SkillsNetwork/Data%20Files/historical_automobile_sales.csv) and includes:
- Automobile sales figures
- Advertising expenditure
- Unemployment rates
- Recession indicators
- Vehicle types and time variables

## Technologies Used

- Python
- Dash by Plotly
- Plotly Express
- Pandas

## How to Run the Project

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/automobile-sales-dashboard.git
   cd automobile-sales-dashboard

## Install dependencies

pip install dash pandas plotly

## Run the app

python dashy.py

## Open your browser 

http://127.0.0.1:8051
