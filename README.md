## Python Project: Wrangling, Merging, and Visualizing Data from NFL Fantasy stats, the NFL Draft, and the NFL Combine from the years 2017,2018, and 2019.
This project uses data from three different sources, all from the same time period: the years 2017,2018, and 2019. The first data source is an Excel file of NFL Combine data compiled from https://nflcombineresults.com/. The second source contains NFL draft data scraped from https://www.pro-football-reference.com. The third source contains NFL Fantasy data retrieved from the API of https://www.fantasyfootballdatapros.com/.

After wrangling and cleaning the data sources, each will be loaded into Tables into a SQLLite database using the Python SQLAlchemy library. The Tables will then be joined in pairs in SQL and loaded back into Python dataframes.

Finally, several visualizations will be created to explore the relationships between varaibles in the merged data.
