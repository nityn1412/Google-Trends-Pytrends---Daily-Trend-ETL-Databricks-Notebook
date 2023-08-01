# Google-Trends-Pytrends---Daily-Trend-ETL-Databricks-Notebook

1. Pytrends Demo ETL Notebook :
   a. Extracting Google Trends daily trending search term in countries using pytrends (pandas dataframe is returened)
   b. Tranforming pandas dataframe into spark dataframe, renaming column, adding trending search term with country, trend rank & date
   c. Loding data into databricks table

2. Generic Google Trends Extraction Using pytrends :
   Parameterized(country field) extraction & transformation notebook to make seperate job for each country to run in parallel(not supported in DB Community Edition)
