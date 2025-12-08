Assessing Links between Climate Disasters, Climate Change, and Economic Impact through a Full Data Lifecycle

Contributors: Veronica Liu and Maggie Cheng

Summary: [500-1000 words] Description of your project, motivation, research question(s), and any findings.

The goal of our project is to explore the relationship between recent global environmental trends and economic outlook over the past 5 years. The negative consequences of climate change have become increasingly evident. We can see the change through more intense and frequent natural disasters, loss of biodiversity, rising sea levels, extreme temperatures, and increased food scarcity. Environmental disruptions have led to profound implications for not only ecosystems but also human society. Local communities face displacement, infrastructure damage, and reduced access to essential resoucres, which poses a long-term threat to economic development and resilience. Climate change is a global issue, but its impacts are felt more in different areas. For example, some countries are more vulnerable due to its geographic location, economic structure, or even adaptive capacity. Our project aims to highlight how economic impact varies across regions and to find meaningful differences in how environmental chane influences national and global economic stability.

We plan to analyze datasets that capture both environmental and economic effects. Some climate-related data that we will analyze include greenhouse gas emissions, frequency and severity of natural disasters, temperature anomalies, and biodiveristy loss indicators. We will focus on metrics such as GDP growth, unemployment rate, average household income, and infrastructure spending. By combining these two datasets, we can identify correlations, emerging trends, and potential links to environmental changes and economic outcomes. This includes investigating how disaster severity correlates with economic slowdowns, how different sectors respond to climate shocks, and whether countries with higher emissions face distinct economic trajectories compared to those with lower environmental footprints. Analyzing these ongoing patterns between the environment and the economy can help guide future policy decisions and increase public awareness of the scope and urgency of climate change impacts.

Climate change is one of the most urgent and complex challenges. Understanding its economic implcations is important for guiding effective policy decisions. Increasingly frequent events such as wildfires, hurricanes, droughts, and floods produce substantial economic losses such as destroyed homes, disrupted supply chains, reduced labor productivity, and strained government budgets through emergency response and recovery efforts. These events also contribute to rising insurance costs, reduced investor confidence, and heightened volatility in financial markets. Climate related risks often interact with existing structural issues, such as income inequality, limited healthcare access, or insufficient infrastructure, compounding overall economic vulnerability. This project will specifically investigate whether patterns in disaster frequency, severity, and associated economic damages correlate with broader economic trends and carbon emissions. By analyzing these relationships, we hope to answer several key questions, which will be stated below.

Our analysis will determine whether observable patterns in disaster frequency, severity, and cost align with changes in economic indicators. We aim to assess whether increases in climate disasters correspond with shifts in GDP growth, altered labor market conditions, or fluctuations in key economic sectors such as agriculture, manufacturing, and energy. We also plan to examine the relationship between carbon emissions and economic performance and explore whether higher emission countries experience different economic pressures compared to lower emission countries. By quantifying the economic burden of climate disasters relative to global GDP and tracking how they evolve over time, we can identify growing vulnerabilities or areas of resilience.

Ultimately, the motivation for this project is to recognize that climate change is not only an environmental issue but also a  economic one. Policymakers, economists, and climate scientists increasingly emphasize the need for integrated strategies that address both climate risks and economic resilience. By analyzing how climate related pressures influence economic outcomes, our research can help with resource allocation, policy design, and global adaptation strategies. Our findings aim to contribute to a deeper understanding of the interconnectedness of environmental and economic systems.

Questions we aim to answer throughout the course of this report include:
What types of natural disasters cause the most economic stress?
How has the frequency and severity of climate events changed over the past 5 years?
What is the relationship between economic strains from climate events and overall economic outlook across different countries?
Are economic costs from environmental disasters increasing or decreasing over the past few years?

Our questions are aimed to guide our goal in identifying how much increasing natural disasters and climate change will effect global-level economic outlooks. 

Aside from our main goal of our research we will follow a responsible full data lifecycle approach from acquisition, storage, cleaning, data quality analysis, provenence, and reproducibility and transparency plans. Furthermore we will follow important ethical and legal constraints of any datasets used while undergoing our project. 

Data profile: [500-1000 words] Description of each dataset used including all ethical/legal constraints.

Dataset 1: "Global Climate Events and Economic Impact Dataset (2020-2025)" from Kaggle

Source and Provenance: "Global Climate Events and Economic Impact Dataset (2020-2025)" from Kaggle. This dataset explores over 3000 recent climate events with important metrics such as type, country, and severity. It also indicates the economic impact of event in dollars, cost of international aid, and impact per capita. This dataset will be key to exploring patterns in severity and economic impact between different countries over time. This dataset is sourced from Google and is in CSV format. https://www.kaggle.com/datasets/uom190346a/global-climate-events-and-economic-impact-dataset

Structure and Coverage: The dataset comprises 20 variables including temporal identifiers (date, year, month), geographic location (country, latitude, longitude), event characteristics (type, severity, duration), human impact metrics (affected population, deaths, injuries), and economic indicators (direct economic losses, infrastructure damage, international aid received). Each event is assigned a unique identifier and classified by type into categories such as Tsunami, Hurricane, Drought, Heatwave, and Wildfire.

Data Collection Methods: Data was collected and compiled from Google. The severity scores (1-10 scale) represent standardized assessments based on multiple factors including affected population, economic losses, and infrastructure damage.

Temporal and Geographic Coverage: The dataset spans six years, providing recent data during a period of heightened climate concern. Geographic coverage is global, with events recorded across multiple countries and continents. The affected population ranges from 622 to over 56 million people per event, reflecting the diverse scale of disaster impacts.

Ethical and Legal Considerations: This dataset involves information about human casualties and suffering, requiring careful ethical treatment. The dataset contains aggregated individual impacts to event-level statistics. It uses publicly available information only. No personally identifiable information is included. The dataset acknowledged that casualty figures may be incomplete due to reporting gaps, particularly in regions with limited infrastructure. It has also recognized potential biases in disaster reporting, which may overrepresent events in developed countries with better monitoring systems.

License: Creative Commons Attribution–ShareAlike 4.0 (CC BY-SA 4.0). This liscents permits reuse, adaptation, redistribtion, and transformation of the dataset for any purpose as long is proper citation is given and modified dataset must be used under the same license. 


Dataset 2: "World GDP, Population & CO2 Emissions Dataset" from Kaggle

Source and Provenance: This dataset aggregates global-level economic and environmental indicators over a 46-year period. This dataset was compiled using information from Worldometer (worldometers.info), a widely used source for global statistics. It has used data from sites such as Worldometer , World Bank, IMF, UN, and Global Carbon Project. These data represent official statistics compiled by international organizations from national government reports.

Structure and Coverage: The dataset contains 11 variables measured annually at the global level: real GDP in constant US dollars, GDP growth rates, GDP per capita, world population, population change metrics, total CO2 emissions from fossil fuels, emissions change rates, per capita emissions, and population density. Each observation represents aggregate global values for a single year.

Data Collection Methods: Global economic data are compiled by the World Bank and UN from national statistical offices using standardized System of National Accounts methodologies. Population estimates come from UN Population Division demographic models based on censuses, vital registration systems, and sample surveys. CO2 emissions data are collected from International Energy Agency fossil fuel consumption statistics and cement production data, using standardized emission factors.

Temporal Coverage: The 46-year time series (1977-2022) provides sufficient historical depth to identify long-term trends while remaining relevant to current climate policy discussions. The most recent years, 2020-2022, overlap with our disaster dataset, enabling integrated analysis. However, 2023-2025 economic data were not available at the time of analysis, which limits our ability to examine the most recent trends.

Ethical and Legal Considerations: This dataset comprises aggregate, national-level statistics without individual-level information, minimizing privacy concerns. However, several ethical considerations do apply, such as the economic aggregates that may mask inequality and differential impacts across populations, the global averages may obscure important regional variations in emissions responsibility and climate vulnerability, historical emissions data reflect cumulative contributions to climate change which raises questions of historical responsibility versus current emissions levels, and finally, population statistics which may have involved sensitive nationality and residency questions for displaced people.

License: This dataset does not include a formal open-data license. The dataset was shared on Kaggle without a specific license defaulting it to all-rights-reserved status. Therefore the raw data is not redistributed in this repository. Instead, we provide instructions for independent download and only share our findings for educational purposes. 

Data quality: [500-1000 words] Summary of the quality assessment and findings.

There are everal quality considerations in the first dataset. Economic impact estimates vary in completeness and methodology across different events and regions because developing countries may have less comprehensive damage assessments than developed nations. Additionally, casualty figures are reported as they become available and may be revised as post-disaster assessments continue. The dataset also likely underrepresents smaller-scale disasters that are not reported on international reporting mechanisms. 

While our second dataset comes from reliable sources, several limitations do exist. GDP measurements face challenges in capturing informal economies, non-market production, and environmental degradation. Population estimates for countries without recent censuses rely on demographic models with uncertainty while CO2 emissions calculations depend on fuel consumption statistics and standardized emission factors that may not reflect actual emissions. Global aggregates also assume comparability across national statistical systems that may use different methodologies.

We conducted data quality assessments for both datasets by ensuring qualities such as completeness, validity, consistency, and accuracy checks. We created profiling scripts that generated descriptive statistics, identified missing values, detected duplicates, validated data types, and checked range constraints. 

The disaster dataset demonstrated completeness across most fields. Of the 3,000 records with 20 variables, we found zero missing values in identification and classification variables. Latitude and longitude values were complete for all events. However, certain impact metrics showed expected patterns of missingness. The deaths field contained 1,247 zero values, approximately 41.6%, which we can interpret as events with no reported fatalities. Similarly, injuries showed 892 zero values, approximately 29.7%, and international_aid_million_usd contained 2,341 zeros, approximately 78.0%. This means that these events either didn't trigger international response or aid amounts were unreported. We differentiated true zeros of no casualties, no aid from unreported/missing values by looking at event severity and economic impact patterns. We found that zero casualties predominantly occurred in low-severity events.

We validated all fields against expected ranges and formats. Severity scores appropriately ranged from 1-10 with a mean of 3.79. This indicates that there is a majority of low-to-moderate severity events. Economic impacts ranged from $0 to $718.21 million per event, which shows a right-skewed distribution of disaster losses. Duration values of 0-115 days fell within reasonable ranges for different disaster types. Quick-onset events such as tsunamis, hurricanes had shorter durations than slow-onset events such as droughts, heatwaves.

Date parsing also identified no invalid date values and they all fell within the documented 2020-2025 range. Geographic coordinates were validated against country locations but we noticed that some events, particularly large-scale events, have coordinates representing approximate centroids rather than precise impact locations.
We also examined logical consistency across related fields by verifing derived total_casualties field against source data. Cross-tabulation of event_type against severity, duration, and economic impact showed that tsunamis and hurricanes showed higher average severity than droughts and heatwaves while wildfires had the longest mean duration when comapared to rapid-onset events like tsunamis.
There was 12 duplicate records that were removed. These likely were data entry errors or multiple reports of the same event. No inconsistencies were found after duplicate removal.

We assessed accuracy through cross-validation with external sources for a sample of high-impact events. We compared casualty figures and economic loss estimates against international disaster database reports. We found notable underestimation in some developing-country events, which suggests reporting gaps.

The GDP/CO2 dataset also showed perfect completeness across all 46 years and 11 variables. This means that in the official statistics, estimates are generated even when direct measurements are unavailable. This completeness does mask underlying estimation uncertainty in years and variables where direct observations were limited.
All numeric values in this dataset fall within expected ranges. GDP values showed consistent growth from $24 trillion in 1977 to $90.8 trillion in 2022, with only one negative growth year during the COVID-19 pandemic. Population figures increased from 4.2 to 8.0 billion. CO2 emissions ranged from 19 to 38.5 billion tons annually, showing the expected increasing trend. Per-capita metrics were validated from total values and population denominators, with no errors detected. We analyzed yearly changes for any jumps that might indicate data errors. All annual changes fell within expected ranges, especially 2020 anomalies, which are well-documented pandemic effects, not data quality issues.

While the data itself is high-quality, we can see that there are limitations in global aggregates. GDP calculations involve purchasing power parity adjustments and currency conversions with associated uncertainties. CO2 emissions estimates rely on energy consumption statistics and emission factors, with typical uncertainty ranges of 5-10% for developed countries and 15-20% for developing countries. 

We standardized column names across both datasets to follow consistent naming conventions such as making strings lowercase and using underscores instead of spaces, which improves and reduces errors. The GDP dataset column names contained special characters which was converted to be standard format. Disaster event dates were parsed from string format to proper datetime objects. Malformed dates were handled even though no invalid dates were observed. For disaster casualty and aid fields, we replaced NaN values with zeros after determining that these represented true zeros rather than missing data. We decided that truly unreported events would be missing across multiple related fields, while zero values appeared selectively in consistent patterns.

We created several derived fields to support analysis:

impact_per_person_usd: Economic impact divided by affected population. Zero-population events was handled by replacing with NaN rather than allowing infinite values.
total_casualties: Sum of deaths and injuries for overall human impact measure.

When integrating datasets, we verified completeness and correctness. The LEFT JOIN preserved disaster data while matching available economic data. We observed that 2023-2025 disaster events lacked corresponding GDP/CO2 data which limited analysis to 2020-2022. We confirmed that all year values in the integrated dataset matched source data. Disaster aggregations were validated by checking sums and averages


Findings: [~500 words] Description of any findings including numeric results and/or visualizations.

In our supporting code file under Exhibit 5: Summary Statistics we have summarized our numerical results utilizing the final cleaned and integrated datasets. From the 'complete_data' subset of the integrated dataset which includes disaster data and global GDP, we found that the total number of recorded climate events from 2020-2022 is 1,531, total estimated economic impact is 3,856.1M, total recorded deaths is 7373, and total individuals affected as 1,289,138,664. Across the 2020–2022 period, the number of climate disaster events remains high, with several hundred events recorded each year. The average severity score between 2020-2021 stays consistently between 3.7 and 3.9 but the tlta economic impact and number of people affected have greater variability. This indicates despite severity in climate disasters, the economic impact and total affected can have various other causes. 

The overall human impact from disasters is substantial, with the data showing over 7000 deaths, 117685 injured, and 1.29 billion affected. Due to the sheer amount of lives affected on a global level, it is important to understand the financial impact on these communities. 

Moving forward to more specific relationships with economic outlooks, the integrated datasets are able to align climate disasters with global economic indicators such as GDP. Specifically from 2020-2022, we see inconsistent GDP growth with 2020 having -0.0288, 2021 going back positive at 0.0635, and 2022 slowing growth at 0.0324. While the total economic impact from natural disasters was highest in 2020 at 1972.3MUSD, and could possibly contribute to negative GDP, COVID was a major cause of slowing global markets. Other standout statistics include the increase CO2 emissions per capita, which grew from 4.56 - 4.8 in just 3 years, with CO2 change only being negative in 2020 also due to COVID-related factors. Due to the nature of the limited time horizon of this dataset, there is no clear decreasing or increasing trend between global climate disasters and global economic indicators. Further analysis on a more regional or national scale would be necessary to understand more direct links. However, for our purpose it can be assumed on a larger-global the economic impacts from natural disasters are absorbed or redistributed evenly across populations, indicating no clear direct relationship. 

Our overall key takeaways are that climate-related disasters remain prevelant and widely impactful despite the number scale of severity. The severity of scores remain stable but the deaths, injuries, and economic losses are variable due to other regional factors. 
 



Future work: [~500-1000 words] Brief discussion of any lessons learned and potential future work.

Our experience integrating disaster event data with annual economic indicators shows the importance of alignment in multi-source analyses. The overlap between datasets is sufficient for initial exploration but there is limited statistical power. Future projects should prioritize datasets with substantial overlap or explicitly design data collection to improve integration. We also learned that different levels of data require different aggregation strategies to avoid losing important variation.

Our data quality assessment showed us that it is essential for credible analysis. Creating automated profiling scripts and structured quality reports ensured systematic coverage of completeness, validity, and consistency. The checksums for data integrity verification were particularly useful and we recommend using this for any project where data provenance and reproducibility matter. 

We initially envisioned more extensive statistical analyses but had to adjust our scope to focus on patterns and descriptive statistics. This ensured we could complete a thorough, well-documented analysis rather than superficially covering many topics. It is better to start with core questions and a solid foundation, then expand if time permits, rather than attempting comprehensive coverage from the start.

Since our analysis is aggregated globally, it also obscures important regional patterns. Future work should be to analyze disasters at country or regional level to identify differential impacts. There should be a link created to country-level GDP and emissions data for more economic impact assessments. We should also incorporate more geographic variables, such as coastal vs. inland, latitude, elevation, etc. to test hypotheses about climate vulnerability.

Although our analysis was primarily descriptive, future work could include developing time-series models to forecast disaster trends and implement regression analyses to quantify relationships between disasters, emissions, and economic variables while controlling for confounders. We could also apply machine learning techniques to predict high-impact events based on economic and climate indicators

Aside from improving the scope and power of the statistical analysis, we learned various lessons on successfully going through each step of the data lifecycle ethically and transparently. 

Acquiring reliable data, analyzing data quality, and adhering to any legal constraints is the foundation of strong data analysis. From the planning phase to the acquisition stage, we had to make various changes to which datasets were best to use for our specific goals given considerations such as licenses, ethical reusability, and suitability for integration. Our original dataset from the World Development Indicator dataset had contained excessive and unnecessary complexity for analyzing at a high-level, and would have been difficult to integrate with any other datasets used. Additionally, we learned how much licensing constraints vary across datasets, even if they are from similar sources. Our final dataset choices themselves had different licensing constraints which we needed to adapt the reproducibility around. In future work, we would aim to improve legal clarity in our datasets with more open-licensed alternative datasets that can also be easier to reproduce for others. 

Furthermore, reproducibility was a priority throughout each stage of the project so we were able to successfully document the necessary steps. However, in future work we hope to explore more opportunities for workflow automation. Our current artifacts and analysis can be reproduced using the provided supplementary notebook and various manual steps, but utilizing other workflow tools such as Snakemake can provide a more efficient experience. Additionally, data cleaning tools such as OpenRefine and its downloadable history can provide a clearer and quicker map to reproducing results. Because our project utilized only two datasets with limited high-level analysis, any future projects with more complex datasets can provide opportunities to increase reproducibility and workflow efficiency. 

By applying lessons learned in automating workflows, data acquisition, clear legal and ethical constraints, and analytical depth we can develop and further evolve our project in the future. We are equipped with a multitude of technical skills, tools, and ethical understanding to scale this project on both further findings and more efficient reproducibility. 

Reproducing: 

1. Access our GitHub repository at: https://github.com/mchen237/IS477-Course-Project

   Clone the repository using these commands in your terminal:
   
   git clone https://github.com/mchen237/IS477-Course-Project
   
   cd IS477-Course-Project

2. Our project was primarily developed using Python 3.10
   
   Install all required libraries listed in requirements.txt by running:
   
   pip install -r requirements.txt 

3. Folder Setup and Data Acquiring

Due to licensing restrictions on the raw datasets, they cannot be redistributed in this repository. You must download them individually and locally through links provided.

All required raw data, input files, processed data, artifacts, and code to run will all be included in the Box folder link. 

Box Folder Name: IS477_Final_Project
Box Link: https://uofi.box.com/s/h93ghmg2o84rmc1sg7wr0lzgaj4xg84d 

After downloading the box and the fiiles inside, place the floder inside the repository so that it matches the format in the box. Furthermore, the .gitignore file ensures that downloaded data is not accidentally pushed to GitHub.

4. Run the Workflow

To reproduce the analysis open either Jupyter Notebook or VS Code, open your repository folder will all necessary inputs and artifacts, open Run_All.ipynb specifically and execute the notebook. 

The workflow will validate SHA-256, clean and preprocess the datasets, create a DuckDB database, perform dataset integration, export cleaned datasets, and generate summary tables, reports, and visualizations. 

To ensure completion of the workflow the following output files should be created in your directory: disasters_clean.csv, gdp_clean.csv, integrated_yearly.csv, climate_economy.duckdb, data_quality_report.txt, integration_report.txt


References: 

Datasets

- Ignacio Azúa. *World GDP, Population and CO2 Emissions Dataset*. Kaggle. Available at: https://www.kaggle.com/datasets/ignacioazua/world-gdp-population-and-co2-emissions-dataset  
  (Accessed 2025). Shared for educational use only.

- UOM190346A. *Global Climate Events and Economic Impact Dataset (2020–2025)*. Kaggle. Licensed under CC BY-SA 4.0.  
  https://www.kaggle.com/datasets/uom190346a/global-climate-events-and-economic-impact-dataset

Software and Libraries

- Python Software Foundation. Python 3.10. https://www.python.org/
- McKinney, Wes. *Pandas: Python Data Analysis Library*. https://pandas.pydata.org/
- DuckDB Foundation. *DuckDB Embedded Database*. https://duckdb.org/
- NumPy Developers. *NumPy scientific computing package*. https://numpy.org/
- Matplotlib Developers. *Matplotlib Visualization Library*. https://matplotlib.org/


