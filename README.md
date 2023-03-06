# NETFLIX_MOVIES_AND_TV_SHOWS_CLUSTERING
The project is based on a Netflix dataset that contains information about movies and TV shows available on Netflix as of 2021. The dataset has 7787 rows and 12 columns. The objective of the project is to analyze the data and draw insights from it.

The first step is to handle the null values in the data. We replace null values in the 'director' column with 'unknown', null values in the 'cast' column with 'no_cast', null values in the 'country' column with 'mode', and null values in the 'date_added' column with 'drop'.

Next, we convert some of the columns containing list of values into lists, add new features such as the number of directors, casts, genres, and countries. We also analyze columns such as 'type', 'director', 'cast', 'country', 'date_added', 'release_year', 'rating', 'duration', 'genre', 'title', and 'description'.

The data shows that most of the content gets uploaded in the beginning and the middle of the month, and there were notable spikes in the number of releases in the months of October, November, December, and January. The content was mainly released between 2010 and 2021. The most frequent listed duration for TV shows is season 1 and for movies it's between 90 to 120 minutes. In the movies, the international movies genre is the most popular on Netflix, followed by drama and comedy. In the TV shows, the ranking is the same.

We also applied clustering algorithms to find similar shows based on their crew and category information. We divided the data into three groups and applied the k-means clustering algorithm to group the shows based on their genre, country, and release year.

In conclusion, this project provides insights into the Netflix dataset and shows how we can analyze such datasets to extract valuable information.

