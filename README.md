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

Analysis and Insights

Global Refugee Trends: Socioeconomic and Behavioral Patterns

The trend of the global numbers of refugees shows a sharply ascending path since the mid-20th century and characteristic spikes of acute geopolitical crises of the type we have witnessed in the early 1990s and following 2010, respectively, which correspond precisely to the Rwandan genocide and the Syrian war, respectively. These findings illustrate the immensely destructive human toll of war violence and indicate a high correlation of political instability, forced displacement, and humanitarian crises.

The Syrian Arab Republic in 2016 generated more than five million refugees—and demonstrated the massive impact of persistent civil war. It was then followed by Afghanistan and South Sudan, demonstrating the ongoing instability in these areas. This pattern not only sheds light on the geopolitics of the crisis of refugees, but also acknowledges the need for an inquiry into the root behavioural consequences of chronic conflict and instability in social society.

Psychological determinants of trauma and of resilience and coping become the bases upon which humanitarian response and policy formulation are called upon. In addition, the data shows a high correlation of GDP per capita and refugee outflow. The scatter plot quite strongly shows that poor nations proportionally generate high numbers of refugees, a natural correlation of material and forced migration vulnerability.

These findings strongly support behavioural and psychological theory—in the theory of Maslow's hierarchy of needs—and the argument that security, safety, and stability of material affairs directly affect group and personal behaviour. In conditions where they are being frustrated by political and economical instability, displacement is the normal outcome. This is a finding of great behavioural scientific implications, in that it indicates reactions to prevention of refugees will need to extend beyond short-term humanitarian interference to the fixing of underlying national and at-community-level economic and stability vulnerabilities.

Thus, psychological resilience-building interventions and proactive socioeconomic investments notwithstanding, forced migration pressure can be overcome by building stable, self-sustaining, and resilient societies that are not so susceptible to displacement.

Finally, there is evidence of a crucial, unseen factor: the psychological and behavioural causes of forced migration. Consequently, policy will need to embrace psychological and socioeconomic paradigms if it is to effectively address proximate and underlying causes of the refugee crisis.







