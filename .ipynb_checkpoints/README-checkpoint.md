Refugee Flows Analysis (2010–2022)

Overview
This project examines global refugee movements between 2010 and 2022 using UNHCR data and investigates how socioeconomic factors (GDP per capita and Human Development Index) from the World Bank relate to those flows.

Files

RefugeeFlowsAnalysis.ipynb — the Jupyter notebook containing all code, analysis and visualisations

data/unhcr/ — raw UNHCR refugee CSV files

data/wb/ — raw World Bank GDP per capita and HDI CSV files

How to run the analysis

Clone the repository to your local machine

Open RefugeeFlowsAnalysis.ipynb in Jupyter Notebook or JupyterLab

Execute each cell in order to reproduce the full workflow

Key steps in the notebook

Import and profile the raw data

Clean and harmonise country names and missing values

Merge the datasets on country and year

Perform exploratory data analysis and flag anomalies

Build a simple linear regression model to predict refugee flows

Summarise insights and suggest next‑step recommendations