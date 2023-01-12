# tmdb_api
## For start, you need to get API key
[How to get a TMDb API Key](https://docs.themeluxury.com/movieasap/getting-started/how-to-get-a-tmdb-api-key/)

## make_own_db.py
This script loads the descriptions for 1000 movies into the `MyFilmDB.json` file.

#### How to use
Open project directory from cmd
```
$ py make_own_db.py
```
Accepts input [API Key v3](https://www.themoviedb.org/settings/api)

![Desktop Screenshot 2023 01 11 - 21 32 51 58](https://user-images.githubusercontent.com/105148929/211833548-e08880eb-028e-45cb-8e69-8f1b3b925c40.png)

## find_similar.py
This script finds similar movies

#### How to use
Open project directory from cmd
```
$ py find_similar.py
```
- Accepts an input path to the database. From the last step, this is `MyFilmDB.json`.
- Next, enter the name of the movie, the code will display the names of similar movies.

![Desktop Screenshot 2023 01 12 - 16 21 22 09](https://user-images.githubusercontent.com/105148929/212028117-357cc3ec-923f-4288-93bb-ce459450d5f9.png)

