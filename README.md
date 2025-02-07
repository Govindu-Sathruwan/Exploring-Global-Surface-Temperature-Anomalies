# Exploring-Global-Surface-Temperature-Anomalies

## Description  
This project investigates how Earth's surface temperature anomalies have varied across different geographical zones and explores monthly and seasonal variations using historical data.

## Research Question  
How have Earth’s surface temperature anomalies varied across different geographical zones, and what patterns can be observed in the monthly and seasonal variations of the surface temperature anomalies?

## Relevance  
Global warming has become an increasingly critical issue in recent years. Understanding long-term trends and patterns in temperature anomalies is essential for addressing climate change. By analyzing temperature anomalies across different geographical zones and temporal scales, this project provides insights into regional and seasonal variations.

## Data Source
The primary data source for this project is NASA’s Goddard Institute for Space Studies (GISS), specifically the GISTEMP v4 dataset. The datasets used include:

• Global-mean monthly, seasonal, and annual means (1880-present): https://data.giss.nasa.gov/gistemp/tabledata_v4/GLB.Ts+dSST.csv   
• Southern Hemisphere-mean temperature anomalies: https://data.giss.nasa.gov/gistemp/tabledata_v4/SH.Ts+dSST.csv   
• Northern Hemisphere-mean temperature anomalies: https://data.giss.nasa.gov/gistemp/tabledata_v4/NH.Ts+dSST.csv    
• Zonal annual means: https://data.giss.nasa.gov/gistemp/tabledata_v4/ZonAnn.Ts+dSST.csv  

## Tools & Technologies Used
• Python (Google Colab)  
• Pandas (Data manipulation)  
• Matplotlib & Seaborn (Data visualization)  
• Power BI (Data visualization)  

## Data Preparation
The raw data was processed using the following steps:  
   1. Data Tidying: The datasets were transformed into a long format using the melt function for better analysis.  
   2. Handling Missing Values: Missing values were identified and replaced appropriately.  
   3. Outlier Detection: Box plots were used to detect outliers, and decisions were made on whether to retain or remove them.  
   4. Data Type Consistency: Data types were standardized for consistency.  

## Exploratory Data Analysis (EDA)
The EDA included:  
• Univariate Analysis: Histograms, box plots, and descriptive statistics to understand the distribution of temperature anomalies.  
• Multivariate Analysis: Time series analysis, scatter plots, and correlation matrices to explore trends and relationships  

## Key Findings
• Global temperature anomalies have increased over time, with a noticeable exponential rise in recent years.  
• Winter seasons are more affected by rising anomalies, particularly in the Northern Hemisphere.  
• The Northern Hemisphere has experienced higher anomalies compared to the Southern Hemisphere.  
• The Arctic region (64N-90N) is heating up the fastest, supporting concerns about melting ice caps.  

## Data Storytelling
The findings from the analysis were communicated through a compelling data story that highlights:  
• The increasing trend in global temperature anomalies.  
• Seasonal variations, showing how winters are more affected.  
• Geographical patterns, emphasizing the impact on the Northern Hemisphere and the Arctic.  

## References
• GISTEMP Team, 2024: GISS Surface Temperature Analysis (GISTEMP), version 4. NASA Goddard Institute for Space Studies. Dataset accessed 2024-12-14 at https://data.giss.nasa.gov/gistemp/  

• Lenssen, N., G.A. Schmidt, M. Hendrickson, P. Jacobs, M. Menne, and R. Ruedy, 2024: A GISTEMPv4 observational uncertainty ensemble. J. Geophys. Res. Atmos., 129, no. 17, e2023JD040179, doi:10.1029/2023JD040179  

• Cheung, H. (2020), What does Trump actually believe on climate change? BBC News, 24 January, Available at: https://www.bbc.com/news/world-us-canada-51213003 [Accessed: 05/01/2025]   

• NASA Science Editorial Team (2019), A Degree of Concern: Why Global Temperatures Matter, NASA, Available at: https://science.nasa.gov/earth/climate-change/vital-signs/a-degree-of-concern-why-global-temperatures-matter/#hds-sidebar-nav-15 [Accessed: 03/01/2025]   

• Noor, D. (2024), Trump continues to deny climate crisis as he visits hurricane-ravaged Georgia: Ex-president refers to climate crisis as ‘one of the great scams’ and plans to attend two fundraisers in oil-rich Texas, The Guardian, 1 October, Available at: https://www.theguardian.com/us-news/2024/oct/01/trump-visits-georgia-denies-climate-crisis-after-hurricane-helene [Accessed: 05/01/2025]   

• United Nations, The Paris Agreement, un.org, Available at: https://www.un.org/en/climatechange/paris-agreement [Accessed: 05/01/2025]  
