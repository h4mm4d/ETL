# ETL
## Overview 
Extract, Transform, and Load (ETL) is an important part of the data management process.  In ETL process data extracts from data sources and cleaned and moved to a central host. The exact steps in that process might differ from one ETL tool to the next, but the result is the same. The goal of ETL is to present data in a format that could easily be summarized and displayed to decision makers. In this assignment the three steps Extract, Transform, and Load was achieved by four deliverables. 

##Results 

#### ETL Function Test
- Data is extracted from CSV files and Jason to Pandas dataframe
- goal was to create three dataframe 
    - wiki_movies_df
    - kaggle_matatada
    - and ratings

#### Extract and Transform Wikipedia Data 
- Here using functions from deliverable one afain dataframe was created and the then data was cleaned for wikipedia data. 
    - wiki_movie_df was again created 
    - used try except to catch errors 
    - this time clean dataframed used to create dataframe
    
 #### Extract and Transform the Kaggle Data
 - In this task using previous two deliverables Kaggle data was cleaned and merged with wikipedia dataframe 
     - then the table was merged with movie ratings 
     - A dataframe movies_with_ratings_df was created

#### Create the Movie Database
- This is the Load function of ETL where data were loaded into a database.    
- Deliverable here is Movies.png to show that data was successfully loaded
     
 
![movies.png](https://github.com/h4mm4d/ETL/blob/main/Resources/movies_query.PNG?raw=true)
![ratings.png](https://github.com/h4mm4d/ETL/blob/main/Resources/ratings_query.png?raw=true)