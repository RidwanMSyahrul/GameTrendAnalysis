# Gaming Trend Analysis
## Introduction
Gaming Industry is pretty big nowadays. Almost everyone have ever tried playing games, whether it's on console or desktop. The variety of the game itself is vast, that we called genre, like shooting, action, puzzle, arcade, etc. The purpose of this project is to analyze the trend of gaming industry from year-to-year based on their sales, genre of game, and their respective platform. This analysis can be useful for marketing team and for developer team because here they could know how is the market liking these kind of games and they could make the decision  tomake what type of games based on the data we shared here.

## Objective
The objective of this project is to provide information regarding game trend throughout the years from the data acquired and that has been analyzed and visualized using Kibana dashboard.

## File info
### Main Folder:
- P2M3_Ridwan_Syahrul_data_raw.csv: This is the dataset used in this project, consist of 11,493 games with their sales detail. This dataset was acquired from [Kaggle](https://www.kaggle.com/datasets/gregorut/videogamesales)
- P2M3_Ridwan_Syahrul_data_clean.csv: This is the clean dataset obtained after doing an ETL using P2M3_Ridwan_Syahrul_DAG.py script.
- P2M3_Ridwan_Syahrul_ddl.txt: This script is a query to make an empty table on PostgreSQL for the raw data that will be send to the server.
- P2M3_Ridwan-Syahrul_DAG.py: This script is a Directed Acyclic Graph, consist of command of doing ETL and it will be executed in Apache Airflow.
- PPT_M3_Ridwan.pptx: This is a powerpoint for this project.

### Dashboard and Images Folder
This folder consist images of the project dashboard on Kibana.
