Updates on each of the tasks described on the project plan including references to specific artifacts in your repository (such as datasets, scripts, workflows, workflow diagrams, etc)

We have completed the majority of initial data exploration, analysis and data lifecycle mapping for the project. Since the completion of the project plan, we have replaced the World Development Indicator dataset with a new dataset for a World GDP and Emissions dataset. "https://www.kaggle.com/datasets/ignacioazua/world-gdp-population-and-co2-emissions-dataset?select=World_GDP_Population_CO2_Emissions_Dataset.csv". This dataset is much cleaner and directly related to our purpose while the WDI dataset has many features we did not need to focus on. Within our project code we have loaded both csv datasets as pandas dataframes and performed initial exploratory analysis such as shapes, missing values, columns, info(), and more. We also included data integrity checking (SHA-256) through checksums completing data collection and acquisition. 

We have also completed storage and organizational artifacts for our final project which utilized DuckDB to create three tables. This assists in simple aggregation of statistics such as yearly climate disasters or total economic loss per year. 

Furthermore, we have made progress in an initial cleaning and integration of the two datasets to create a compact dataframe that joined yearly disasters with GDP and carbon emission values. To clean the dataframes we converted the dates into datetime format, removed any missing entries, retitled column names, and ensured standardized value formatting. 

To assess data quality, we have also began evaluating each dataset based on the 4 factors of completeness, consistency, timeliness, and accuracy. So far, we have completed evaluation of completeness and consistency with our intial data analysis. Overall, both datasets have very few missing values and most columns have consistent formatting espeically after cleaning. To further evaluate the data for accuracy we will cross-reference with other trusted sources on natural disasters. 

An updated timeline indicating the status of each task and when they will be completed

Identify key regions for analysis. Initial data exploration and Data Lifecycle mapping. (Veronica, completed)

Clean and create a master dataset (Maggie, completed)

Normalize and assess quality of the dataset. Further break down data into cost, changes in frequency and severity, etc. (Veronica, completed)

Create visualizations and compute statisical results for factors impacting climate recovery (Maggie, in progress)

Create outline of findings and create report of findings (Both, in progress)

Our main next steps are to analyze the data further with supplemental visualizations, further cleaning using OpenRefine, and completion of documentation related to workflows, reproducability, and the metadata. 

A description of any changes to your project plan itself, in particular about your progress so far. Also include changes you made to your plan based on feedback you may have received for Milestone 2.

Our main change to our project so far was the replacement of the WDI dataset with a simplified GDP and Carbon Emissions dataset. With this change we had to adjust some of our main research questions, as less details can be provided. With this addition, we had to adjust citation details such as licenses and integration details in our final report. Additionally we have expanded the noted gaps in our plan by including the dataset's reproducibility, automation, metadata.

Each team member has to write a short summary of their contributions to the current milestone. Each team member should add and commit their contribution summary themselves to the shared github repo.

Veronica: Primarily focused on the initial analysis, preprocessing, and storage of the data. Completed initial data explorations for both datasets, generated integrity checks, and utilized DuckDB for a relational storage system to create new tables. I also began the documentation of the data quality assessment in the four areas in our final report. 

Maggie: Cleaned both datasets by identifying whether there were any missing or invalid values within the dataet, then replacing the missing values, and once cleaned, merged both datasets into a master dataset.


