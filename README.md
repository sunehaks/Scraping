# Scraping
contains my work on scraping data:
scraping_practice.py : contains few practice samples I tried while learning scraping

project_scrape.py : contains logic to scrape username, ratings and reviews from the below link.

Scrape_title.py : Contains logic to scrape movie titles(1000) from the link : https://www.imdb.com/search/title/?countries=in 
and also logic to access further links that contains movie information , mainly the ratings and reviews of the users using the links present in the above web page.
Scrape_title then writes these to three files:
movies_scrape1.csv : contains movieId and title
ratings_scrape1.csv : contains userId, movieId and ratings given by that particular user to that particular movie.
reviews_scrape1.csv : contains userId, movieId and reviews given by that particular user to that particular movie.

These files were further utilized by model based item-item collaborative filtering program to recommend movies.
