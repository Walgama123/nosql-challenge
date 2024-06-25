
<h1 align="center">No SQL Data Manipulate & Analysis with pymongo </h1>


## Background
The UK Food Standards Agency evaluates various establishments across the United Kingdom and gives them a food hygiene rating.
In this project, it is going to be manipulated and analyzed restaurant information stored in a json file by importing to the MongoDb (No SQL) database.

## Data sources
- [Source data -establishments.json](Resources/establishments.json)

## Tools and python libraries used
- MongoClient in pymongo

## Activities 
- Import data from Json files using “mongoimport”.
- Create a mondo db client to deal with the database server.
- List databases/ Collections  in the MongoDB server
- Find an existing record. 
- Doing CRUD operation using pymongo.

## Exploratory Analysis
- Count the number of records for a given criteria. 
- Search data with aggregation.
- Sort and limit the search results data. 
- Store  the results data in a pandas DataFrame.

# Folders and files.
- Root folder
  - [NoSQL_setup_starter.ipynb](NoSQL_setup_starter.ipynb)
  - [NoSQL_analysis_starter.ipynb](NoSQL_analysis_starter.ipynb)
  
- Resources folder
  - [establishments.json](Resources/establishments.json)