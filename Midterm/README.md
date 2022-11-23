# DA320 Midterm project
Author: Heather Marie | 
Contributers: Ted Spence, Vincent Hong, Jamie Kirsila, Natalia Sadkov

# MongoDB Scraper for Metacritic movie data
The MongoDB Scraper pulls information about movies from the year 2000 through 2020 and compiles them in a database for querying.

# MongoDB Dashboard for Metacritic movie data
The MongoDB Dashboard reads the Metacritic data and performs an analysis comparing the performance of two types of movies. 

- Create XY scatter plot of movie scores by Metacritic by year 2000-2020
Shows a reduced number of movies scored between 2005 and 2010.  May be correllated to reduced number of media journalists due to economic changes and media mergers.

- Compare overlaid histograms of Metacritic movie scores from years 2014 and 2020
Shows an improved average score of movies scored in 2020 from 2014.  May be correllated to improved movie technology, or a change in the market for scores improving as audience tastes change over time.

- Comparing overlaid histograms of all movie scores by keywords comparing 'Wedding' to 'War' on Metacritic
Shows a significantly higher number of movies including the keyword 'War' over 'Wedding', reflecting the market offerings in movie media from 2000 to 2020.

# Credentials file
The Credentials.json file is a secure private file which retains the connection string to the MongoDB database repository.  It is not committed to GitHub as listed in the .gitignore file.

# GitIgnore file
Prevents the Credentials file from being committed to GitHub main.

# License.md
MIT license allows sharing of this code for noncommercial use.