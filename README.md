# Movie-Marathon-Analysis
Understanding user watch patterns for movies using SQL

Acces to two tables
Table 1 :Movies 
o movie_id (INT, PRIMARY KEY) 
o title (VARCHAR) 
o genre (VARCHAR) 
o duration_minutes (INT) 

Table 2:  WatchHistory 
o watch_id (INT, PRIMARY KEY) 
o user_id (INT) 
o movie_id (INT, FOREIGN KEY references Movies.movie_id) 
o watch_date (DATE) 

create two tables and inserted values respectively for each tables.

written query to  retrieve the user_id, the total number of distinct movies_watched, and the total_watch_duration_minutes for each user. 
