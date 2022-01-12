#Project2--Suicide-data-Visualization

Meet the Team 5: Michael Lapiana, Margot Rudy, Shreyansh Saraiya, and Jenny Yang

Suicide Data Visualization Death by suicide is sensitive topic that causes pain to hundreds of thousands of people every year around the world. There is a need for it to be investigated in order to learn from it and possibly prevent it. According to estimates from the World Health Organization (WHO), Suicide is the second leading cause of death among 15-29 years old and over 800,000 people die because of it every year. These large numbers motivated us to work on this topic. We found that the data is workable and not too complex to pick apart.

Dataset: https://www.kaggle.com/russellyates88/suicide-rates-overview-1985-to-2016?select=master.csv datasize: 2.71MB https://raw.githubusercontent.com/datasets/geo-countries/master/data/countries.geojson

Link of Repo: https://github.com/mlapiana/Project-2-Suicide-data-visualization

Our project contains a website with at several views of our data; including a Suicide Chloropleth Map to control dashboard by year and country with handle clicks to change all views based on new choice from the map, visualization of a bubble chart for Suicides by Age, and pie charts for Gender and Generation for selected Country/Year. It is a 5 page website, with 1 map and a dashboard, with pages 2-5 detailed by Age, Gender, Generation and Country. Our project utilizes a Flask server with an API endpoints, and our Flask server can pull data from our database before returning it to our website. Our project also uses PostgreSQL.The JavaScript library that we did not cover in class was JQuery, which helped create our Pie and Bar graphes and our Metadata Box.

FILES INCLUDED IN THE REPO: 2 JUPYTER NOTEBOOKS - ETL (FOR DATA TRANSFORMATION AND GENERATING DATABASE), GEOJSON MODIFICATION- GENERATE GEOJSON THAT FEEDS INFO TO THE MAP, Query.sql to assign primary key to table, APP.PY - RETURN FLASK SERVER TO RETURN THE VIEWS, TEMPLATE FOLDER- 5 HTMLS- to make each page, JSon Files- 8 to generate content in the web for each webpage, and CSS- file for styling

BELOW ARE THE INSTRUCTIONS ON HOW TO OPEN PROJECT:

Open PgAdmin as a management tool for PostgreSQL. Be sure to put in the password for access. Create a new database entitled "Suicide_db".

Open the the file ETL.ipynb in your Jupyter notebook (do not forget to enter source activate PythonData38 before opening your notebook or you may run into some problems. You can run the code on each line. Be sure to clear your kernals first. Your scripts should run correctly as you see the dataframes merge. We decided that mergeing was easier than joining for every API.

Your tables should now show in PgAdmin. Run the Query. You will need to do this to assign the Primary Key. As you run the query you should see that the database is ready to be read by the website.

Produce your GeoJson in the Jupyter notebook- this will feed into your map. 4a) If you are recreating this whole project, you need to go to mapshaper.org to shrink your data files. We named our file as "_reduced" to keep track. This saved space for the project. It is also important to note to hide your API keys and your passwords.

Finally,Run Flask on the Jupyter notebook. '

To run the site properly you must first enter the year in the drop down before you choose which country you would like the data on.

Our project Utilized the following: ETL: *Clean in Jupyter notebook and load data in SQL, JQuery-used to popupate data to communicate w javascript library, Popper -visualization, Bootstrap -visualization, D3 -visualization, Plotly -visualization, Javascript-coding, Leaflet-design, Python - coding, Jupyter - query, json- database, Pandas - coding, SQLAlchemy -database, PgAdmin- database, html- style, css- style, ETL: *Clean in Jupyter notebook and load data in SQL Define database schema , app.py: Build a Flask Server for API endpoints


