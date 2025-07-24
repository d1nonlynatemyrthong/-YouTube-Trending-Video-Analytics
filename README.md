YouTube-Trending-Video-Analytics
# YouTube Trending Video Analytics

## Project Overview

This project analyzes YouTube trending video data from different countries (India, US, UK) to identify patterns in content performance, audience sentiment, and regional differences. The goal is to explore what makes videos trend, how long they stay trending, and how user engagement varies by genre and country.

## Objectives

- Clean and preprocess multi-country YouTube datasets
- Perform sentiment analysis on video titles and tags
- Use SQL to analyze engagement metrics and category trends
- Create Tableau dashboards to visualize insights
- Summarize findings in a report using data storytelling

## Tools and Technologies

- Python (Pandas, TextBlob, SQLite)
- SQL (via SQLite3 in Jupyter Notebook)
- Tableau Public (for dashboarding)
- Jupyter Notebook

## Project Phases

### Phase 1: Data Cleaning and Preprocessing (Python)

- Combined datasets from India, US, and UK
- Converted date formats 
- Handled null values and standardized fields
- Added custom features such as `publish_to_trend` and `trending_days`
- Performed sentiment analysis using TextBlob on video titles and tags
- Saved the cleaned data to `youtube_trending_cleaned(1).csv`

### Phase 2: SQL-Based Analysis

Used SQLite and SQL queries within Jupyter Notebook to:

- Rank video categories by average views and likes
- Analyze sentiment distribution per country
- Measure average days it takes for a video to trend
- Evaluate how long videos stay trending

All SQL query results were saved as CSV files to be used in Tableau.

### Phase 3: Tableau Visualization

Imported the processed CSV outputs into Tableau to design:

- Category-wise and country-wise viewership trends
- Sentiment distribution charts
- Comparisons of likes vs dislikes across categories
- Trending behavior over time

The dashboard was exported as a `.twbx` file and also as a `.pdf`.

### Phase 4: Report Generation

A final report was created summarizing the key insights, visualizations, and observations based on the dashboard. It covers:

- Which categories are most engaging in each region
- Differences in sentiment across countries
- Trends in publish timing vs trending success
