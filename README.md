# Netflix-Movies-Recommender

This recommender system is designed on the approach of content-based filtering. The content based filtering method for this project is based on the actors, directors, titles and genres of the movies.

The data set used for this recommender was created to list all shows available on Netflix streaming, and analyze the data to find interesting facts. This data was acquired in May 2022 containing data available in the United States. Hire is the link to the source of the data https://www.kaggle.com/datasets/victorsoeiro/netflix-tv-shows-and-movies

# Content

## This dataset has two files containing the titles (titles.csv) and the cast (credits.csv) for the title.

## This dataset contains +5k unique titles on Netflix with 15 columns containing their information, including:

- id: The title ID on JustWatch.
- title: The name of the title.
- show_type: TV show or movie.
- description: A brief description.
- release_year: The release year.
- age_certification: The age certification.
- runtime: The length of the episode (SHOW) or movie.
- genres: A list of genres.
- production_countries: A list of countries that produced the title.
- seasons: Number of seasons if it's a SHOW.
- imdb_id: The title ID on IMDB.
- imdb_score: Score on IMDB.
- imdb_votes: Votes on IMDB.
- tmdb_popularity: Popularity on TMDB.
- tmdb_score: Score on TMDB.

## And over +77k credits of actors and directors on Netflix titles with 5 columns containing their information, including:

- person_ID: The person ID on JustWatch.
- id: The title ID on JustWatch.
- name: The actor or director's name.
- character_name: The character name.
- role: ACTOR or DIRECTOR.
