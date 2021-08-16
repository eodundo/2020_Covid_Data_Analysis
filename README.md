# Covid-19 Data Analysis
This is a descriptive analysis describing 2020 Covid data by graphically presenting statistics to show what happened.
•	Data Source:  Ourworldindata.org/coronavirus &  data.europa.eu/data/datasets/covid-19-coronavirus-data
•	Data Cleaning was done in Jupyter Notebook and basically involved dropping irrelevant columns that did not contribute to the visualization/interpretation of the data and filling the null columns.
•	Model data: The cleaned data was then used to create and design a sqlite database with structured tables.
•	Created a connection to PostgreSQL server using Psycopg2 and a primary key
•	Python Flask App was used to query and structure the data and create routes.
o	Challenge experienced at this point: the flask app could not render the database and read the data. I kept getting an error. Eventually I picked a json file from the same website and used it for visualization.
•	Chart.js (a JavaScript Library) was used to generate line graphs.
•	 Interpreting data involves selecting three countries of your choice from the dropdown and the resulting chart will display a comparison of covid cases and covid deaths in selected countries between Jan-2020 to Dec-2020.
