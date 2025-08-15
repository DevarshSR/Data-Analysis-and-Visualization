Movie Analysis
This project analyzes a dataset of 9,000 movies sourced from the TMDB API. The analysis covers genre frequency, voting patterns, popularity metrics, and trends over time.

Dataset
The dataset contains information about movies, including:

Release_Date: Date when the movie was released
Title: Name of the movie
Overview: Brief summary of the movie
Popularity: Metric computed by TMDB based on views, votes, favorites, watchlists, release date, and other factors
Vote_Count: Total votes received from viewers
Vote_Average: Average rating out of 10
Original_Language: Original language of the movie
Genre: Movie categories
Poster_Url: URL of the movie poster
Analysis Goals
Q1: Identify the most frequent genre in the dataset
Q2: Determine which genre has the highest total votes
Q3: Find the movie with the highest popularity and its genre(s)
Q4: Discover which year has the most movies filmed
Data Cleaning Steps
Removed unnecessary columns: Poster_Url, Original_Language, Overview
Dropped rows with null values
Converted Release_Date to year
Ensured Vote_Count and Vote_Average are numeric
Transformed the Genre column so each genre appears in a separate row
Key Findings
Most Frequent Genre: Drama
Genre with Highest Votes: Drama
Most Popular Movie: Spider-Man: No Way Home (Genres: Action, Adventure, Science Fiction)
Year with Most Movies: 2020
Usage
Clone the repository.
Ensure you have Python and the required libraries (pandas, numpy, matplotlib, seaborn).
Place the dataset (mymoviedb.csv) in the data directory.
Run the analysis notebook: Movie_analysis.ipynb.
License
This project is for educational and analytical purposes. Data is sourced from TMDB API.

Author
Movie Analysis by Devarsh S R

