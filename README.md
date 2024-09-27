NOSQL- Challenge
This project demonstrates how to import data into a MongoDB database and interact with the data using a Jupyter Notebook. 
It covers the process of using the mongoimport function to load a JSON file into a MongoDB collection and then connecting to the database using PyMongo within a Jupyter Notebook.


Import the Data into MongoDB
Use the mongoimport function to import the provided establishments.json file into a new MongoDB database called uk_food:

mongoimport --type json -d uk_food -c establishments --drop --jsonArray starter_code/Resources/establishments.json

This repository contains the following documents. Jupiter File
Starter Code
1. Resources
2. NoSQL_analysis_starter.ipynb
3. NoSQL_setup_starter.ipyb




References
UK Food Standards AgencyLinks to an external site. (2022). UK food hygiene rating data API. https://ratings.food.gov.uk/open-data/en-GBLinks to an external site.. Contains public sector information licensed under the Open Government Licence v3.0Links to an external site.
Accessed Sept 9, 2022 and Sept 12, 2022 with the establishment settings as follows: longitude=51.5072, latitude=-0.1276, maxdistancelimit=4567, pagesize=10000, sortoptionkey=distance, pagenumber=(1,2,3,4,5,6,7,8).
