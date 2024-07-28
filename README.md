# Module 6 Challenge - Retrieving Data from APIs

## NY Times API Retrieval

The first section creates the variables needed to create the url to connect to the NY times. Once the url is created, it 
is used to connect to the NY Times and retrieve the data needed for analysis. Then the data is cleaned to a standard format,
this will allow it to be combined with other data more easily. The keywords are moved to a list and the titles are then isolated
which will allow them to match the movie database.

## The Movie Database API Retrieval

The query is created to retrieve movie data from the API. The title list from the previous section is used to retrieve a movie id,
the movie ID is used to get the needed data from the API. The data is then cleaned to be the same format as the data from the 
NY Times API. 

## Combined Data

The data is then merged to have the data for the matching titles from both sources. The combined data then has the uneeded
characters and columns removed. Duplicates are removed. The combined clean data is then saved as a csv. 

## Citations

-[General Data Structure in NY Times API](https://developer.nytimes.com/docs/articlesearch-product/1/routes/articlesearch.json/get)

-[General API Information for the Movio Database](https://developer.themoviedb.org/reference/search-movie)

-[List to string](https://www.geeksforgeeks.org/python-program-to-convert-a-list-to-string/)

-[delete clomn in dataframe](https://stackoverflow.com/questions/13411544/delete-a-column-from-a-pandas-dataframe)

-[Drop duplicate rows](https://www.geeksforgeeks.org/python-pandas-dataframe-drop_duplicates/)

-[Use Loop to delete characters](https://www.freecodecamp.org/news/how-to-remove-a-specific-character-from-a-string-in-python/#for-loop)



 