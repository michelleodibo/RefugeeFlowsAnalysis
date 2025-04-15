Refugee Flow Analysis

This repository analyzes the worldwide forced migration trends by correlating UNHCR refugee figures of the period 1951-2022 against World Bank economics figures in the context of GDP per capita figures of the period 2010-2018. In a self-contained Jupyter notebook called RefugeeFlowsAnalysis.ipynb, the project illustrates the pipeline of acquiring the raw CSV data, standardizing country names, and generating three significant visualizations: a long-term time series of worldwide totals of the refugees, a bar plot of the top ten origin nations of the latest year, and a scatter plot investigating the correlation of the outflow of refugees and country GDP per capita.

Inside the data directory, there is a collection of the raw data: UNHCR exports in data/unhcr and cleaned World Bank data in data/wb. It is easy to recreate the analysis by cloning this repository, opening the notebook in Jupyter Notebook or JupyterLab, and running the cells in sequence. There is explanation along the code to outline questions being asked, actions being undertaken to address them, and conclusions about the scale and drivers of displacement globally.

Data have been supplied both by the World Bank and the UN High Commissioner for Refugees.

Key steps in the notebook

Import and profile the raw data

Clean and harmonise country names and missing values

Merge the datasets on country and year

Perform exploratory data analysis and flag anomalies

Build a simple linear regression model to predict refugee flows

Summarise insights and suggest next‑step recommendations