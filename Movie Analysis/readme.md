# 🎬 Movie Analysis

A comprehensive analysis of **9,000 movies** sourced from the **TMDB API**, exploring **genre trends, voting patterns, popularity, and yearly production**.

---

## 📊 Dataset Description
This dataset contains information about **9,000 movies** from the TMDB API.

### **Columns Description**
- **Release_Date**: Date when the movie was released.  
- **Title**: Name of the movie.  
- **Overview**: Brief summary of the movie.  
- **Popularity**: Metric computed by TMDB based on views, votes, favorites, watchlists, release date, and other factors.  
- **Vote_Count**: Total votes received from viewers.  
- **Vote_Average**: Average rating out of 10.  
- **Original_Language**: Original language of the movie.  
- **Genre**: Categories the movie can be classified as.  
- **Poster_Url**: URL of the movie poster.  

---

## 🎯 Analysis Objectives
1. **Q1:** What is the most frequent genre in the dataset?  
2. **Q2:** Which genre has the highest votes?  
3. **Q3:** What movie has the highest popularity? What are its genres?  
4. **Q4:** Which year has the most movies filmed?  

---

## 🧹 Data Cleaning Steps
- Dropped unnecessary columns: `Poster_Url`, `Original_Language`, `Overview`
- Removed rows with null values
- Converted **Release_Date** to **year**
- Ensured **Vote_Count** and **Vote_Average** are numeric
- Transformed **Genre** column so each genre appears in a separate row

---

## 📌 Key Findings
- **Most Frequent Genre:** 🎭 Drama  
- **Genre with Highest Votes:** 🎭 Drama  
- **Most Popular Movie:** 🕷 *Spider-Man: No Way Home*  
  - **Genres:** Action, Adventure, Science Fiction  
- **Year with Most Movies:** 📅 2020  

## Author

Movie Analysis by Devarsh S R
