**Movie Analysis**
A comprehensive analysis of 9,000 movies sourced from the TMDB API, exploring genre trends, voting patterns, popularity, and yearly production.

Dataset Description
This dataset contains information about 9,000 movies from the TMDB API.

Columns Description
Release_Date: Date when the movie was released.
Title: Name of the movie.
Overview: Brief summary of the movie.
Popularity: Metric computed by TMDB based on views, votes, favorites, watchlists, release date, and other factors.
Vote_Count: Total votes received from viewers.
Vote_Average: Average rating out of 10.
Original_Language: Original language of the movie.
Genre: Categories the movie can be classified as.
Poster_Url: URL of the movie poster.
Analysis Objectives
Q1: What is the most frequent genre in the dataset?
Q2: Which genre has the highest votes?
Q3: What movie has the highest popularity? What are its genres?
Q4: Which year has the most movies filmed?
Data Cleaning Steps
Dropped unnecessary columns: Poster_Url, Original_Language, Overview
Removed rows with null values
Converted Release_Date to year
Ensured Vote_Count and Vote_Average are numeric
Transformed Genre column so each genre appears in a separate row
Key Findings
Most Frequent Genre: Drama
Genre with Highest Votes: Drama
Most Popular Movie: Spider-Man: No Way Home (Genres: Action, Adventure, Science Fiction)
Year with Most Movies: 2020
Usage
Clone this repository.
Ensure you have Python and the following libraries installed:
pandas
numpy
matplotlib
seaborn
Place the dataset (mymoviedb.csv) in the project directory.
Open and run Movie_analysis.ipynb in Jupyter Notebook or VS Code.
Conclusion
Drama is the most frequent and most voted genre.
Spider-Man: No Way Home is the most popular movie.
2020 saw the highest number of movies filmed.
License
This project is for educational and analytical purposes. Data is sourced from TMDB API.

Author
Movie Analysis by [Your Name]

