# Google-Trends-Pytrends---Daily-Trend-ETL-Databricks-Notebook


1. Pytrends Demo ETL Notebook :

   a. Extracting Google Trends daily trending search term in countries using pytrends (pandas dataframe is returened)

   b. Tranforming pandas dataframe into spark dataframe, renaming column, adding trending search term with country, trend rank & date

   c. Loding data into databricks table

   Direct Notebook Link - https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/8881205802088401/1717380898652080/1939591732392236/latest.html

2. Generic Google Trends Extraction Using pytrends :

   Parameterized(country field) extraction & transformation notebook to make seperate job for each country to run in parallel(not supported in DB Community Edition)

   Direct Notebook Link - https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/8881205802088401/2387488636523229/1939591732392236/latest.html

