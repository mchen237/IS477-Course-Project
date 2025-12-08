Assessing Links between Climate Disasters, Climate Change, and Economic Impact through a Full Data Lifecycle

Contributors: Veronica Liu and Maggie Cheng

Summary: [500-1000 words] Description of your project, motivation, research question(s), and any findings.

The goal of our project is to explore the relationship between recent global environmental trends and economic outlook over the past 5 years. The negative consequences of climate change have become increasingly evident. We can see the change through more intense and frequent natural disasters, loss of biodiversity, rising sea levels, extreme temperatures, and increased food scarcity. Environmental disruptions have led to profound implications for not only ecosystems but also human society. Local communities face displacement, infrastructure damage, and reduced access to essential resoucres, which poses a long-term threat to economic development and resilience. Climate change is a global issue, but its impacts are felt more in different areas. For example, some countries are more vulnerable due to its geographic location, economic structure, or even adaptive capacity. Our project aims to highlight how economic impact varies across regions and to find meaningful differences in how environmental chane influences national and global economic stability.

We plan to analyze datasets that capture both environmental and economic effects. Some climate-related data that we will analyze include greenhouse gas emissions, frequency and severity of natural disasters, temperature anomalies, and biodiveristy loss indicators. We will focus on metrics such as GDP growth, unemployment rate, average household income, and infrastructure spending. By combining these two datasets, we can identify correlations, emerging trends, and potential links to environmental changes and economic outcomes. This includes investigating how disaster severity correlates with economic slowdowns, how different sectors respond to climate shocks, and whether countries with higher emissions face distinct economic trajectories compared to those with lower environmental footprints. Analyzing these ongoing patterns between the environment and the economy can help guide future policy decisions and increase public awareness of the scope and urgency of climate change impacts.

Cliamte change is one of the most urgent and complex challenges. Understanding its economic implcations is important for guiding effective policy decisions. Increasingly frequent events such as wildfires, hurricanes, droughts, and floods produce substantial economic losses such as destroyed homes, disrupted supply chains, reduced labor productivity, and strained government budgets through emergency response and recovery efforts. These events also contribute to rising insurance costs, reduced investor confidence, and heightened volatility in financial markets. Climate related risks often interact with existing structural issues, such as income inequality, limited healthcare access, or insufficient infrastructure, compounding overall economic vulnerability. This project will specifically investigate whether patterns in disaster frequency, severity, and associated economic damages correlate with broader economic trends and carbon emissions. By analyzing these relationships, we hope to answer several key questions, which will be stated below.

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

Dataset 2: "World GDP, Population & CO2 Emissions Dataset" from Kaggle

Source and Provenance: This dataset aggregates global-level economic and environmental indicators over a 46-year period. This dataset was compiled using information from Worldometer (worldometers.info), a widely used source for global statistics. It has used data from sites such as Worldometer , World Bank, IMF, UN, and Global Carbon Project. These data represent official statistics compiled by international organizations from national government reports.

Structure and Coverage: The dataset contains 11 variables measured annually at the global level: real GDP in constant US dollars, GDP growth rates, GDP per capita, world population, population change metrics, total CO2 emissions from fossil fuels, emissions change rates, per capita emissions, and population density. Each observation represents aggregate global values for a single year.

Data Collection Methods: Global economic data are compiled by the World Bank and UN from national statistical offices using standardized System of National Accounts methodologies. Population estimates come from UN Population Division demographic models based on censuses, vital registration systems, and sample surveys. CO2 emissions data are collected from International Energy Agency fossil fuel consumption statistics and cement production data, using standardized emission factors.

Temporal Coverage: The 46-year time series (1977-2022) provides sufficient historical depth to identify long-term trends while remaining relevant to current climate policy discussions. The most recent years, 2020-2022, overlap with our disaster dataset, enabling integrated analysis. However, 2023-2025 economic data were not available at the time of analysis, which limits our ability to examine the most recent trends.

Ethical and Legal Considerations: This dataset comprises aggregate, national-level statistics without individual-level information, minimizing privacy concerns. However, several ethical considerations do apply, such as the economic aggregates that may mask inequality and differential impacts across populations, the global averages may obscure important regional variations in emissions responsibility and climate vulnerability, historical emissions data reflect cumulative contributions to climate change which raises questions of historical responsibility versus current emissions levels, and finally, population statistics which may have involved sensitive nationality and residency questions for displaced people.


Data quality: [500-1000 words] Summary of the quality assessment and findings.

There are everal quality considerations in the first dataset. Economic impact estimates vary in completeness and methodology across different events and regions because developing countries may have less comprehensive damage assessments than developed nations. Additionally, casualty figures are reported as they become available and may be revised as post-disaster assessments continue. The dataset also likely underrepresents smaller-scale disasters that are not reported on international reporting mechanisms. 

While our second dataset comes from authoritative sources, several limitations do exist. GDP measurements face challenges in capturing informal economies, non-market production, and environmental degradation. Population estimates for countries without recent censuses rely on demographic models with uncertainty while CO2 emissions calculations depend on fuel consumption statistics and standardized emission factors that may not reflect actual emissions. Global aggregates also assume comparability across national statistical systems that may use different methodologies.


Findings: [~500 words] Description of any findings including numeric results and/or visualizations.

Future work: [~500-1000 words] Brief discussion of any lessons learned and potential future work.

Reproducing: Sequence of steps required for someone else to reproduce your results.

References: Formatted citations for any papers, datasets, or software used in your project.

