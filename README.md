# qtm350-final-project

## Group members: Lucas Lobo, Katherine Martini, Joyce Chen, Caleb Sharkey.

## Central Question: 

How do various health-related, economic, and geographic factors contribute towards and interact with life expectancy at birth, mortality rate, and adolescent fertility rate? We will use data from the publicly available WDI (World Development Index) Database. Specifically, we will analyze additional attributes like immunization (measles, DPT, HEPB3), HIV prevalence, urban and rural populations, unemployment rates, and surface area. Our area of focus will be South American, Central American, and Carribean regions from 1975-2024. We will compute descriptive statistics and plots, filtering by year, indicator, country, and region.

## Setup of the repository:

- data folder: this includes the data itself (in a .csv file) and the SQL database, which includes various merged, cleaned, and transformed tables (in a .db file).
- documentation folder: this includes the codebook and an entity-relationship diagram.
- figures folder: this includes notebooks displaying plots and tables generated in the analysis (using our cleaned and transformed data). Most of this analysis uses Python to graph and visualize our indicators. 
- scripts folder: this includes notebooks showcasing various descriptive statistics computed. This analysis uses a combination of SQL commands (connected with a cursor using sqlite3) and Python scripts.

To run the code, you can either clone the repository into your own Github account or download the csv and db files within the 'data' folder and run the  (modifying the file paths accordingly within the Jupyter Notebook files).


## Role Assignments/Division of Work:

1. Github repository:
- README with brief description --> Lucas
- data folder (scrape data with SQL) --> Lucas
- documentation folder with Python code and ER diagram --> Katherine/Joyce
- figures folder with plots and tables --> Katherine/Joyce
- scripts folder with SQL and Python --> Joyce/Lucas

2. Quarto report including Title/Intro, Data Description, Data Analysis, Results/Discussion, and Conclusion --> Caleb.
