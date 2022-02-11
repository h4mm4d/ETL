# ETL
## Overview 
Extract Transform Load (ETL) is an important part of data managemnt process.  In ETL process data is extracted from data sources and cleaned and moved to a central host. The exact steps in that process might differ from one ETL tool to the next, but the end result is the same. The goal of ETL is to present data in a format that could easily be summarized and displayed to decision makers. In this assignment the three steps Extract, Transform, and Load was achived by four deliverables. 

##Results 

#### ETL Function Test
- Data is extracted from CSV files and jason to Pandas dataframe
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
- this is the Load function of ETL where data was loaded into a database.      
- Deliverrable here is Movies.png to show that data was sucessfully loaded 
![movies.png][]