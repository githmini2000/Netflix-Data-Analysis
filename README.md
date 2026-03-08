# Netflix Data Analysis Project

## Overview
This project analyzes Netflix content data to understand ratings, top directors and actors, content trends over the years, and sentiment analysis of descriptions.

## Dataset
- Source: Netflix dataset `netflix_titles.csv`
- Contains information about TV shows and movies including title, director, cast, country, date added, release year, rating, duration, genres, and description.

## Steps Performed
1. **Data Exploration**
   - Checked dataset shape, columns, and summary statistics.
2. **Rating Analysis**
   - Counted content ratings and visualized distribution using a pie chart.
3. **Top 5 Directors**
   - Identified directors with the most content on Netflix.
4. **Top 5 Actors**
   - Identified actors with the most appearances on Netflix.
5. **Content Trend Analysis**
   - Visualized the number of movies and TV shows produced over years.
6. **Sentiment Analysis**
   - Analyzed the description text of Netflix content for Positive, Neutral, and Negative sentiment using TextBlob.

## Libraries Used
- pandas
- numpy
- plotly.express
- textblob

## Visualization
- Pie charts for rating distribution
- Bar charts for top directors and actors
- Line charts for content trends
- Bar charts for sentiment analysis

## Project Folder Structure
- Netflix-Data-Analysis/
  - data/
    - netflix_titles.csv
  - notebooks/
    - netflix_analysis.ipynb
  - README.md